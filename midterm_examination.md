# Midterm Examination for Computer Science 302 Fall 2020

## Add Your Name Here

## Re-type the sentence "I adhered to the Allegheny College Honor Code while completing this examination."

You must retype the sentence here.

## Dates for the Final Examination

- **Examination Released**: 9:00 AM on Monday, October 19, 2020
- **Examination Due**: 11:59 pm on Wednesday, October 21, 2020

## Honor Code for the Final Examination

- You must adhere to the Honor Code throughout your completion of the examination
- The examination is closed notes, closed book, and closed online resources
- You may use your laptop computer and its text editor and Python programming tools
- You may not refer to the Python source code that you wrote during the semester
- You may not refer to the technical writing that you completed during the semester

**IMPORTANT**: All students in this course are obligated to adhere to the
Allegheny College Honor Code throughout the completion of this examination. If
the instructor detects that a student has committed a likely violation of the
Allegheny College Honor Code, then he will file a report with the Dean of
Students Office. Please make sure that you review the [Honor
Code](https://sites.allegheny.edu/about/honor-code/) before you start to take
this examination. Please note that, due to the ongoing global pandemic, Sections
1 and 2 of Honor Code Article IV are not enforced for this examination.

## Procedures for the Final Examination

- You must provide answers to all these questions by typing in this file
- The final version of this file must be in your GitHub repository by the due date
- You may direct message the course instructor through the Slack workspace if you have questions
- Do not post questions about the examination in a public channel of the Slack workspace
- Unless you make special arrangements with the instructor, no late work will be accepted

## Structure of the Final Examination

- The examination is worth 100 points
- Each question has an assigned point total given in parentheses
- Provide your answer to a question by typing below the subsection header

## (10 Points) Provide a definition of the following terms:

### (2 Points) Web server

### (2 Points) Web browser

### (2 Points) Domain name system

### (2 Points) Web server cache

### (2 Points) Web browser cache

## (10 Points) Please define the following terms related to web sites

### (5 Points) HTTPS

### (5 Points) URL

## (10 Points) Please interpret the output from the following commands

### (5 Points) Output from the `dig` command

```
; <<>> DiG 9.16.6 <<>> github.com
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 28755
;; flags: qr rd ra; QUERY: 1, ANSWER: 1, AUTHORITY: 0, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 4096
;; QUESTION SECTION:
;github.com.                    IN      A

;; ANSWER SECTION:
github.com.             1       IN      A       140.82.114.3
```

What is the IP address of GitHub's servers? How did you know?

### (5 Points) Output from the `mtr` command

```
 Host                            Loss%   Snt   Last   Avg  Best  Wrst StDev
 1. _gateway                      0.0%     5    1.1   1.8   1.1   3.5   1.0
 2. dynamic-acs-72-23-183-1.zoom  0.0%     5    8.6  10.9   8.6  16.1   3.2
 3. 10.201.22.66                  0.0%     5   19.5  13.8  10.4  19.5   4.1
 4. 10.200.2.61                   0.0%     5   10.8  12.3   9.9  14.8   2.0
 5. 10.200.3.34                   0.0%     5   12.4  13.5  11.7  16.2   1.8
 6. 10.200.2.117                  0.0%     5   11.4  14.0  11.4  15.3   1.6
 7. ce-0-6-0-1.r01.nycmny17.us.b  0.0%     5   76.9  39.0  28.7  76.9  21.2
 8. ae-2.r21.nwrknj03.us.bb.gin. 20.0%     5   29.7  30.2  29.7  30.7   0.6
 9. ae-3.r25.asbnva02.us.bb.gin. 20.0%     5   36.0  42.7  33.9  64.8  14.8
10. ae-7.r06.asbnva02.us.bb.gin.  0.0%     5   35.1  53.4  35.1 121.0  37.9
11. ce-0-6-0-1.r06.asbnva02.us.c  0.0%     5   32.2  40.5  32.2  61.2  11.8
15. lb-140-82-112-4-iad.github.c  0.0%     4   33.2  32.0  30.5  33.2   1.2
```

Does data transmission from the client to the server exhibit a lot of
variability? How did you know?

## (10 Points) Define and explain the three "cascading principles" called "inheritance", "specificity", and "location"

## (10 Points) Write some CSS source code that explains how to create:

### (5 Points) An ordered list with three list items

### (5 Points) A hypertext reference to the web site www.allegheny.edu

## (10 Points) Provide a definition of the following HTTP response codes:

### (2 Points) 200:

### (2 Points) 301 or 307:

### (2 Points) 401:

### (2 Points) 404:

### (2 Points) 500:

## (10 Points) Provide a definition of the following terms:

### (2 Points) Inline CSS style

### (2 Points) Embedded CSS style

### (2 Points) External CSS style

### (2 Points) Google Web font

### (2 Points) LAMP stack

## (10 Points) Use plain text, draw a picture of the table that would result from this source code

```html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="utf-8">
   <title>Tabular Data</title>
</head>
<body>
   <table>
      <tr>
         <td>The Death of Marat</td>
         <td>Jacques-Louis David</td>
         <td>1793</td>
         <td>162cm</td>
         <td>128cm</td>
      </tr>
      <tr>
         <td>Burial at Ornans</td>
         <td>Gustave Courbet</td>
         <td>1849</td>
         <td>314cm</td>
         <td>663cm</td>
      </tr>
   </table>
</body>
</html>
```

Please provide your response to this question in a fenced code block.

## (10 Points) Provide a detailed, multiple paragraph response to the following question:

Pick one laboratory or practical assignment that you worked on this semester
that you struggled to understand and solve and explain how the struggle itself
was valuable. In the context of this question, describe the struggle in the
field of web development and how you overcame it through your own actions. In
your response to this question, you might also discuss whether struggling built
aspects of character in you (e.g. endurance, self-confidence, or competence to
solve new problems) and how these virtues might benefit you in later ventures.

## (10 Points) Provide a detailed, multiple paragraph response to the following question:

Suppose that you have a web page in a GitHub repository with a failing build in
GitHub Actions. After explaining an example of a way in which the build might
fail for a web page that uses either tables or forms, please furnish all of the
steps that you would take to understand and fix the build failure. Finally,
please explain how, in addition to looking for the green checkmark in GitHub
Actions, you would know that the web page was fixed correctly.
