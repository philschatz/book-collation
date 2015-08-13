# Differences from actual HTML

- `<include>` might be an `<a>` with additional attributes differentiating it from a regular link
- `<Exercise class="homework">` would actually be `<div data-type="exercise" class="homework">`


# RuleSet notes


- RE `MoveToEndOf`: we could:
  1. have an element in the content like `<Bucket rs-123>` (would have to be duplicated for each chapter)
  2. describe it in the "template" for the book
    - `::div` would actually be `::after`
