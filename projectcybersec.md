---
layout: page
title: Project:CyberSec
permalink: /projectcybersec/
---

![Project:CyberSec]({{ site.baseurl }}/images/line.png "Project:CyberSec")

### Description

Project:CyberSec is an initiative started in May 2019 by TAR UC FOCS. Its objectives are:

- Find and gather TAR UC students who have the skills and interests in Cybersecurity. 

- Build a community of like-minded students and a platform to exchange ideas. 

- Cultivate the culture of participating in Cybersecurity related competition in TAR UC.

This initiative started from a WhatsApp group, and had held activities such as seniors' experience sharing sessions and Capture-The-Flag competition discussions. Currently in-charged by Trailbl4z3r, looking for successor as I am going to graduate.

### Activities Conducted

-- Senior Sharing Session : 
- [Lim Tien Aun](https://www.linkedin.com/in/tien-aun-lim-bab8471b3/)
- [Cheow Jia Jian](https://www.linkedin.com/in/jay-cheow-593b10112/)

-- CTF Competition Participation & Discussion : 
- F-Secure Cyber Security Competiton Malaysia 2019 ~ 2020
- KPMG Cyber Challenge 2019


### Gallery

{% include carousel.html height="50" unit="%" duration="7" %}

### Puzzles

Here are two puzzles that were shared by me for recruitment purpose.

#### Puzzle 1

Objective : Decode a readable string from the picture.

![Puzzle1]({{ site.baseurl }}/images/Puzzle1.PNG "Puzzle1"){: .puzzle1}

[Higher Resolution](/images/Puzzle1.PNG)

[Solution](/images/Answer1.png)

#### Puzzle 2

Objective : Decode the "anoroc_virus" string using the information and function given.

Language : Java

```java
public static void main(String[] args) {
	var virus_dna = "ACCCACAUCUCGAUUUCUAAUUAGACCACCCACGAAUGGGCAUAUACUCACAUCAGCAUUUCAAACUAGACUACACACGAGUGGGCCUAC";
	var virus_shell = "\",5*%npl :5.%xdl :7(1xp~\",5('nrx (7(1jv~ .#(1lrl .5(1np~ .#<1npx\",#(#lrl\",7*%nvx$:1.#nrl";
	var anaroc_virus = "";

	var i = 0;
	for (char c : virus_shell.toCharArray()){
	anaroc_virus += (char)((int)c ^ (int)(virus_dna.charAt(i % virus_dna.length())));
	i++;
}
```

[RAW](/file/puzzle2.txt)

[Solution](/images/Answer2.png)
