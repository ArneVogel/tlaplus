---
title: "Comments"
date: 2021-06-21T14:03:35+02:00
draft: true
---
## Single lines comments
```
Init == hour = 0 \* This is a single lines comment
```

## Multi lines comments
```
(* This is a comment that spans multiple lines 
   explaining how this function works. *)
Init == hour = 0

(* 
    This would also work for a comment
    over multiple lines
*)
Next == hour' = (hour + 1) % 12

(**************************************************************************)
(* Commonly you would also see comments like this in specs                *)
(* Also spanning over multiple lines                                      *)
(**************************************************************************)
Spec == Init /\ [][Next]_hour
```

{{< toc >}}
