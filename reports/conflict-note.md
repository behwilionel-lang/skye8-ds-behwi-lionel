# Merge conflict resolution
I created different changes to the same section of `README.md` on two branches. 
When Git attempted to merge the branches, it reported a content conflict in `README.md`.

I opened the file, reviewed the two versions between the conflict markers,
 chose the final content, and removed the `<<<<<<<`, `=======`, and  markers. I then staged the resolved file and completed the merge with a commit.