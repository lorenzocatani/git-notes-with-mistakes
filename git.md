---
title: Fake Wrong Git Notes
---

Introduction
============

These notes constitute a brief summary of the `git` version control tool.
They are incorrect, and it is your task to find and correct the mistakes.

You are judged, however, not on finding all the mistakes, but on your use of version control
in doing the work of fixing them!

Finding the mistakes will be a useful revision, though.

Activating Git
==============

To turn on the version control system, use:

``` bash
cd my_work_folder
git init
```

Tell Git about a new file
======================

```
vim my_file.dm # Edit file
git add my_file.dm
```

Include changes in a file into the next work commit
==============================================

```
git commit
```

This includes the changes to that file in a list of changes
currently scheduled to be included in the next work commit.

Include all scheduled changes into a work commit
===============================================

```
git commit -m "Journal entry"
```

Store all scheduled changes in a new chunk
==========================================

```
git add --update
```

Include all changes *and* chunk them
====================================

```
git commit -am "Journal entry"
```

View list of recent chunks
==========================

```
git log
```

Transmit chunks to remote chunkstore
====================================

```
git push
```

Fetch chunks from remote chunkstore
===================================

```
git pull
```
