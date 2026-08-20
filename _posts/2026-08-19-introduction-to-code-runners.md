---
layout: post
codemirror: true
comments: True
title: Introduction to Code Runners
description: Learn how to embed interactive Python, Java, JavaScript, and AP CSP pseudocode runners in lessons.
permalink: /code-runners
---

# Introduction to Code Runners

Code runners turn a lesson into an interactive workspace. Students can read a short explanation, change the code, and run it directly on the page. This lesson demonstrates the four languages supported by this site: Python, Java, JavaScript, and AP CSP Pseudocode.

## Python Code Runner

Python is a good starting point because its syntax is concise and its output is easy to inspect. Run the example, then try changing the loop range or adding another message.

{% capture python_challenge %}
Run the code, then customize the greeting or loop so it prints a different sequence.
{% endcapture %}

{% capture python_code %}
print("Hello, World!")
for i in range(5):
    print(i)
{% endcapture %}

{% include runners/code.html
   runner_id="intro-python"
   language="python"
   challenge=python_challenge
   code=python_code
%}

## Java Code Runner

Java uses a class and a `main` method as the entry point. Run the example, then change the greeting or loop condition and observe the output.

{% capture java_challenge %}
Run the code, then change the greeting or make the loop count to a different number.
{% endcapture %}

{% capture java_code %}
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
        for (int i = 0; i < 5; i++) {
            System.out.println(i);
        }
    }
}
{% endcapture %}

{% include runners/code.html
   runner_id="intro-java"
   language="java"
   challenge=java_challenge
   code=java_code
   height="360px"
%}

## JavaScript Code Runner

JavaScript can print values to the console and is especially useful for demonstrating browser-based programming concepts. Run the example, then change the loop or add another `console.log` statement.

{% capture javascript_challenge %}
Run the code, then personalize the message or change the loop limits.
{% endcapture %}

{% capture javascript_code %}
console.log("Hello, World!");
for (let i = 0; i < 5; i++) {
    console.log(i);
}
{% endcapture %}

{% include runners/code.html
   runner_id="intro-javascript"
   language="javascript"
   challenge=javascript_challenge
   code=javascript_code
%}

## AP CSP Pseudocode Runner

AP Computer Science Principles uses a standardized pseudocode language on the exam. The runner supports assignment arrows, input, conditionals, and display statements so students can practice the same style of problem solving interactively.

{% capture pseudocode_challenge %}
Run the calculator with 3, +, and 0 as inputs. Then try another operator or test division by zero.
{% endcapture %}

{% capture pseudocode_code %}
num1 ← INPUT("Enter first number:")
op ← INPUT("Enter operator (+, -, *, /):")
num2 ← INPUT("Enter second number:")
result ← 0
IF (op = "+")
{
    result ← num1 + num2
}
ELSE
{
    IF (op = "-")
    {
        result ← num1 - num2
    }
    ELSE
    {
        IF (op = "*")
        {
            result ← num1 * num2
        }
        ELSE
        {
            IF (op = "/")
            {
                IF (num2 ≠ 0)
                {
                    result ← num1 / num2
                }
                ELSE
                {
                    DISPLAY("Error: Division by zero")
                    result ← "undefined"
                }
            }
            ELSE
            {
                DISPLAY("Invalid operator")
                result ← "undefined"
            }
        }
    }
}

DISPLAY("Result: " + result)
{% endcapture %}

{% include runners/code.html
   runner_id="intro-pseudocode"
   language="pseudocode"
   challenge=pseudocode_challenge
   code=pseudocode_code
   height="560px"
%}

## Embedding a Code Runner in a Lesson

A runner needs a unique `runner_id`, a language, a challenge, and starter code. Capture the challenge and code first, then pass both variables to the reusable include.

{% raw %}
```liquid
{% capture challenge %}
Explain what the code should do.
{% endcapture %}

{% capture starter_code %}
print("Try changing this code")
{% endcapture %}

{% include runners/code.html
   runner_id="my-runner"
   language="python"
   challenge=challenge
   code=starter_code
%}
```
{% endraw %}

For a preset AP CSP example, use the same pattern with `language="pseudocode"` and place the pseudocode inside the capture block. Each runner on a page must have a different ID so its saved code and controls remain independent.

## Why Code Runners Help

Code runners make lessons active instead of read-only. Students can test an idea immediately, compare output, fix errors, and build confidence through small experiments. The same lesson structure works across languages while still letting each language show its own syntax and execution model.
