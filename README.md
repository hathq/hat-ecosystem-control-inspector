# Ecosystem Control Inspector HAT

Independent HATHQ HAT repository. It owns the vocabulary, context plan, exact-term reducer and procedure for `inspect-ecosystem-control`. It contains no credentials and grants no authority. Consumers load the immutable package and invoke its declared worker interface.

The reducer accepts only canonical vocabulary IDs, rejects revision conflicts and returns `vocabulary-term-unknown` for every unrecognized value. Unknown input is never guessed or completed.

