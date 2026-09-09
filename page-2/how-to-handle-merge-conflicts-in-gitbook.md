---
description: Added description
---

# How to handle merge conflicts in GitBook

#### Understand the conflic <a href="#understand-the-conflic" id="understand-the-conflic"></a>

Conflicts can happen when a merge introduces incompatible changes, such as when you edit a content block that has been changed, or you remove files that GitBook is trying to update.

For example, if someone else on your team opens a change request at the same time you do, edits a few blocks and merges it, this will update the primary content. Your branch will be outdated, and you’ll be prompted to update your change request to bring in their changes.

However, if you’ve edited the same blocks as your teammate, you’ll need to decide which version you want to keep, and GitBook will flag it as a conflict.

<a class="button secondary"></a><br>
