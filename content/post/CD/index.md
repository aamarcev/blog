---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Непрерывная интеграция и развертывание"
subtitle: "CD/ID"
summary: ""
authors: [Аркадий Марцев]
tags: []
categories: []
date: 2024-03-16T03:57:20+03:00
lastmod: 2024-03-16T03:57:20+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# Непрерывная интеграция (CI)

Непрерывная интеграция - это практика разработки программного обеспечения, которая заключается в постоянном слиянии рабочих копий в общую основную ветвь разработки (до нескольких раз в день) и выполнении частых автоматизированных сборок проекта для скорейшего выявления потенциальных дефектов и решения интеграционных проблем. В обычном проекте, где над разными частями системы разработчики трудятся независимо, стадия интеграции является заключительной. Она может непредсказуемо задержать окончание работ. Переход к непрерывной интеграции позволяет снизить трудоёмкость интеграции и сделать её более предсказуемой за счёт наиболее раннего обнаружения и устранения ошибок и противоречий, но основным преимуществом является сокращение стоимости исправления дефекта, за счёт раннего его выявления. 

# Непрерывное развертывание (CD)

Непрерывное развертывание - это процесс релиза программного обеспечения, в котором используется автоматизированное тестирование. При этом проверяется правильность и стабильность изменений в базе кода для немедленного автономного развертывания в рабочей среде. Цикл выпуска ПО со временем претерпел изменения. Непрерывное развертывание позволяет быстро доставлять пользователю новую функциональность и не жертвовать при этом качеством. 
