# Boilerplate Code Snippets

This repository contains boilerplate code snippets for quickly setting up basic C and Java programs.

## C Language Boilerplate

To quickly set up a basic C program, you can use the following boilerplate code snippet:

```json
{
    "boilerplate": {
        "prefix": "boilerplate for c",
        "body": [
            "#include<stdio.h>",
            "int main ()",
            "{",
            "    $1",
            "    return 0;",
            "}"
        ],
        "description": "Log output to console"
    }
}
```

## Java Language Boilerplate

To quickly set up a basic Java program, you can use the following boilerplate code snippet:

```json
{
    "Boilerplate": {
        "prefix": "Boilerplate code for java",
        "body": [
            "import java.util.*; //import java.util.Scanner;",
            "",
            "public class $1 {",
            "    public static void main(String[] args) {",
            "        Scanner sc = new Scanner(System.in);",
            "        $2",
            "    }",
            "}"
        ],
        "description": "Log output to console"
    }
}
```

