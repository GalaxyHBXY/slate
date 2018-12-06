### Labelling Example

This file is intended to help learn about text labelling with slate. It is
intended to be read and followed from within slate. If you are in the directory
containing slate, run it like so:

```shell
python3 src/annotate.py example/label-example.md -hh --ann-type categorical --ann-scope token --overwrite
```

When labelling, the current item is underlined. In this case, that means the
very first token of this document.

There are two ways to move the underline:

  >- Use the arrow keys
  >- Or use `j`, `i`, `o`, and `;` to move left, up, down and right, respectively

The reason for the second option is those keys are closer to the next set of
keys, which allow you to change the size of what you have selected:

  >- To expand the item, use `m`, `k`, `l`, and `/` to make it larger to the left, up, down, and right, respectively
  >- To contract the item use the same keys with `SHIFT` (i.e., `M`, `K`, `L`, `?`)

To move, expand and contract faster:

  >- Type a number before any of the above commands and it will be repeated that many times
  >- Hold `SHIFT` while moving to jump to the start/end of a line or top/bottom of the document

Select an item you want to label:

  >- Type `SPACE` and then `a` to apply the 'a' label

Note that the text has changed colour to indicate that it is labeled.

  >- Type `SPACE` and then `a` again to remove the label
  >- Similarly, type `SPACE` and then `s` to apply the 's' label

Note that a different colour is used for each label. These keys and colours can
be defined as you like.

  >- Type `SPACE` and then `a` to also apply the 'a' label

When multiple labels apply to the same item a different colour is used.

  >- Type `u` to remove both labels on this item
