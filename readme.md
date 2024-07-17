# next-turbo

This is an approximation of the workflow used for developing nextjs + turbo.
We keep both repos as submodules and sync the lockfiles to make sure that the
versions are all compatible.

## Testing

The next-build-test crate is a rust-only entrypoint into nextjs that strips
out all of the js-side stuff. Should make it simple enough to validate the
rust build improvements.
