# Elixir Enum.each and Process.exit

This repository demonstrates a potential problem when using `Process.exit` inside an `Enum.each` loop in Elixir.  Improper use of `Process.exit` can lead to unexpected program termination and difficulty in debugging.

The `bug.exs` file shows the problematic code, and `bugSolution.exs` presents a solution to avoid premature termination.