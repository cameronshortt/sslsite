---
title: Halloween Day 4 - Ransomware!
description: Now our flag is being extorted! 
date: 2024-10-04
type: "post"
tags: ["Linux"]
categories: ["Halloween"]
---

Darn it! The evil entity encrypted our flag and wants tons of money for the password.

We figured out that `evil` is a shell script that reads a password on a TCP port, but then we got bored and figured you can do the rest. (it's not that bad, you can take a look at it for us right?)

Can you get our flag so we don't have to pay out?

Mouseover the appropriate line for hints.  Highlight and right click to copy, and right click on cursor to paste.
<div class="mouseover">
    <table>
        <tr>
            <td>Hint 1</td>
            <td class="content">use <code>command &</code> to background a command and <code>fg</code> to focus it</td>
        </tr>
    </table>
</div>
<div class="mouseover">
    <table>
        <tr>
            <td>Hint 2</td>
            <td class="content">netcat :)</td>
        </tr>
    </table>
</div>
<div class="mouseover">
    <table>
        <tr>
            <td>Hint 3</td>
            <td class="content">They're so l33t they use 1337th most common password</td>
        </tr>
    </table>
</div>
<div class="mouseover">
    <table>
        <tr>
            <td>Hint 4</td>
            <td class="content">netcat can be finicky sometimes, try ending input with ^D^C</td>
        </tr>
    </table>
</div>
<div class="mouseover">
    <table>
        <tr>
            <td>Hint 5</td>
            <td class="content">see above, use <a href="log">this</a> if you're super stuck (WARNING: MAJOR SPOILERS)</td>
        </tr>
    </table>
</div>

<link href="/ctf/vm/vm.css" rel="stylesheet"/>
<script src="/ctf/vm/oct4.js"></script>
<div id="virt">
    <iframe src="/ctf/vm/vm.html?url=oct4.cfg&cpu=x86">Incompatible Browser D:</iframe>
</div>
<table id="result" style="visibility=hidden"><tr>
    <td><h1 id="status"></h1></td>
	<td id="link"><a href="https://docs.google.com/forms/d/e/1FAIpQLSe2U40kd2YZ1z-lAdet2ltbJ9bmWXi3YtVB7yn4RoGj66pP7w/viewform">Record your Progress</a></td>
</table>
<textarea id="flag">Type flag here</textarea>
<button onclick="submit();">Submit</button>
