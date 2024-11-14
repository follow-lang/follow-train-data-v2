# Generate train data for follow model

This repo will generate data of `Follow-Lang/set.mm.proof` in huggingface.

## Format

- The data is located in `train/`.
- Each line is formatted as: Cost(s) Cost(a) Cost(s')\t s a s' .
- `a` starts with `<action>` and ends with `</action>`.
- `Cost(s) = max(Cost(a), 1+Cost(s'))`.
- The maximum word length is 1024.
- All vocabulary words are listed in `words.txt`.
- The data was generated with a depth of 2.

If you need additional data, feel free to reach out.

This version improves readability and flow while maintaining the original meaning.