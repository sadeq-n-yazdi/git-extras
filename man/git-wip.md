git-wip(1) -- Create a Work In Progress commit
================================

## SYNOPSIS

`git-wip` [options]

## DESCRIPTION

  Create a Work In Progress commit, include all files in the working directory.

## OPTIONS

  --no-verify, --no-hooks   Skip git hooks verification
  --run-hooks               Run git hooks verification (overrides skip settings)
  -h, --help                Show help message

## EXAMPLES

  Create a WIP commit which stores all changes in the working directory.

    git wip

  Later on, undo the commit and continue making changes.

    git unwip

## AUTHOR

Written by Andrew Sullivan Cant &lt;<mail@andrewsullivancant.ca>&gt;

## REPORTING BUGS

&lt;<https://github.com/tj/git-extras/issues>&gt;

## SEE ALSO

&lt;<https://github.com/tj/git-extras>&gt;
