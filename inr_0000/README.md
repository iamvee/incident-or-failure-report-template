---
title: "A Title"
description: "a short description"
date: 18-04-2019
time: 00:57:00 +4500
project: project-tag
author: "John Smith"
reviewer: "Jane Doe"
---

# Symptoms

_extra data could be shown as tooltip or alt-text of an image as well_


| row | from    |  time     | describe    | effect |   
| :-: | :--     |   :--     | :--         | ------ |
|  1  | Ja'far  | 14:23     | lorem ipsum | link to other sections if available    |
|  2  | Akbar   | 16:00     |             |        |
|     |         |           |             |        |
|     |         |           |             |        |


# Diagnosis

| row | from    |           |             |        |
| :-: | :--     |   :--     | :--         | ------ |
|  1  |         |           |             |        |
|  2  |         |           |             |        |



# logfiles

_dont copy and paste all log file here, just suspicious lines, important error messages and keep the original log file (for higher priorities) in a `zip` or `tar.gz` file._

1.  [link to a copy of log file](#)
<details>

<summary>  

`file_name.log`  

</summary>

    ```shell
    64.242.88.10 - - [07/Mar/2004:16:05:49 -0800] "GET /twiki/bin/edit/Main/Double_bounce_sender?topicparent=Main.ConfigurationVariables HTTP/1.1" 401 12846
    64.242.88.10 - - [07/Mar/2004:16:06:51 -0800] "GET /twiki/bin/rdiff/TWiki/NewUserTemplate?rev1=1.3&rev2=1.2 HTTP/1.1" 200 4523
    64.242.88.10 - - [07/Mar/2004:16:10:02 -0800] "GET /mailman/listinfo/hsdivision HTTP/1.1" 200 6291
    64.242.88.10 - - [07/Mar/2004:16:11:58 -0800] "GET /twiki/bin/view/TWiki/WikiSyntax HTTP/1.1" 200 7352
    64.242.88.10 - - [07/Mar/2004:16:20:55 -0800] "GET /twiki/bin/view/Main/DCCAndPostFix HTTP/1.1" 200 5253
    64.242.88.10 - - [07/Mar/2004:16:23:12 -0800] "GET /twiki/bin/oops/TWiki/AppendixFileSystem?template=oopsmore¶m1=1.12¶m2=1.12 HTTP/1.1" 200 11382
    64.242.88.10 - - [07/Mar/2004:16:24:16 -0800] "GET /twiki/bin/view/Main/PeterThoeny HTTP/1.1" 200 4924
    64.242.88.10 - - [07/Mar/2004:16:29:16 -0800] "GET /twiki/bin/edit/Main/Header_checks?topicparent=Main.ConfigurationVariables HTTP/1.1" 401 12851
    64.242.88.10 - - [07/Mar/2004:16:30:29 -0800] "GET /twiki/bin/attach/Main/OfficeLocations HTTP/1.1" 401 12851
    ```

</details>


# Calls, Messages, and Emails

## phonecall

|                      |                       |
|  --:                | :--                   |
| fromm                | Abbas <+989123456789> |
| to                   |  +210000000           |
| duraton              |                       | 
| symptoms linked      |  [1](#), [2](#)       |
| diagnosis linked     |  [1](#), [2](#)       |


# text messages 

|                      |                       |
|  --:                 | :--                   |
| fromm                | Abbas <+989123456789> |
| to                   |  +210000000           |
| symptoms linked      |  [1](#), [2](#)       |
| diagnosis linked     |  [1](#), [2](#)       |
| message thread/body  |  text                 
                       | 
                       | 
                       |
                       |
                       |


# emails 

mail thread / messages w/ enough info from header 


# actions during incident


# after incident 

## causes, and analysis

## command line history

_activate timelog for terminal sessions_

`john@server`

```bash
ls -lath
ls ./**/i18n/*.po | grep msgif | awk  '{ $1 = "" ; print $0 }' | less
```


`root@server`

```bash
grep -i mail  /var/log/auth.log
```