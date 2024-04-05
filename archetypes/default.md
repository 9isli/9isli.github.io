<<<<<<< HEAD
---
title: "{{ replace .Name "-" " " | title }}"
description: 
date: {{ .Date }}
image: 
math: 
license: 
hidden: false
comments: true
draft: true
---
=======
+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
+++
>>>>>>> 59c2968bf9d83446e3651810ef150c153695147d
