# Hashicorp Configuration Language Features
The official documentation is the best reference for these: https://www.terraform.io/docs/language/index.html

## Expressions
### Strings

    "foo" # literal string
    
    "foo ${var.bar}" # template string

### Operators

    # Order of operations: 
    !, - # (multiplication by -1)
    *, /, % # (modulo)
    +, - # (subtraction)
    >, >=, <, <= # (comparison)
    ==, != # (equality)
    && # (AND)
    || # (OR)

