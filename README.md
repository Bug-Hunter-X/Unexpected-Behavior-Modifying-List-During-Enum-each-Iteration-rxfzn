# Elixir Bug: Modifying List During Enum.each Iteration

This example demonstrates an issue that can arise when attempting to modify a list while iterating over it using `Enum.each`.  The expected behavior of removing elements matching a condition isn't met because `Enum.each` doesn't modify the list directly.