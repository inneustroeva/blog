---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Stepik 1"
summary: ""
authors: [Neustroeva Irina]
tags: []
categories: []
date: 2025-05-04T22:07:55+03:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
# Цель работы
 
Выполненить контрольные задания первого блока "Безопасность в сети" внешнего курса "Основы кибербезопасности".

# Выполнение заданий блока "Основы Кибербезопасности"

## Как работает интернет: базовые сетевые протоколы

Протокол HTTP(S) протокол прикладного уровня, ответ на вопрос 1 - HTTPS (рис. [-@fig:001]).

image: featured.png1
  caption: "featured.png1"
  focal_point: "featured.png1"
  preview_only: truth


На транспортном уровне существует два примера протокола: первый - это TCP, в честь которого названа модель. (рис. [-@fig:002]).

image:featured.png2
  caption: "2"
  focal_point: "Bottom"
  preview_only: false


Т.к адрес состоит из большего набора чисел, а именно это 4 или 6 цифер от 0 до 255. В двух вариантах встречаются цифры больше 255, что неверно(рис. [-@fig:003]).

image:featured.png3 )))
  caption: "3"
  focal_point: "Bottom"
  preview_only: false

Основная задача DNC это сопоставлять название ( доменное имя, с корекстым IP-адресом) с тем, где лежит этот сервер, этот сайт. (рис. [-@fig:004]).

image:featured.png4
  caption: "4"
  focal_point: "Bottom"
  preview_only: false

Классификация протоколов в модели TCP/IP:

- Прикладной уровень: HTTP, RTSP, FTP, DNS.

- Транспортный уровень: TCP, UDP, SCTP, DCCP.

- Сетевой  уровень: IP.

- Уровень сетевого доступа (Канальный) (Link Layer): Ethernet, IEEE 802.11, WLAN, SLIP, Token Ring, ATM и MPLS(рис. [-@fig:005]).

image:featured.png5
  caption: "5"
  focal_point: "Bottom"
  preview_only: false

Протокол http передает не зашифрованные данные, а протокол https уже будет передавать зашифрованные данные (рис. [-@fig:006]).

 https передает зашифрованные данные, поэтому  одна из фаз это передача данных, другая должна быть рукопожатием
 
 image:featured.png6
  caption: "6"
  focal_point: "Bottom"
  preview_only: false

TLS определяется и клиентом, и сервером, чтобы было возможно подключиться (рис. [-@fig:007]).

image:featured.png7
  caption: "7"
  focal_point: "Bottom"
  preview_only: false

TLS определяется клиентом и сервером, чтобы возможно было подключиться (рис. [-@fig:008]).

image:featured.png8
  caption: "8"
  focal_point: "Bottom"
  preview_only: false

Фаза рукопожатия вкючает в себя: 

- выбор параметров, протоколов
- аутентификация (как минимум, сервера)
- формируется общий секретный ключ K 

Следовательно вариант с шифрованием лишний (рис. [-@fig:009]).

image:featured.png9
  caption: "9"
  focal_point: "Bottom"
  preview_only: false

## Персонализация сети

Куки хранят в себе список параметров и их значений. Этими параметрами могут быть id пользователя, id сессии, тип браузера и некоторые действия пользователей(рис. [-@fig:010]).

image:featured.png10
  caption: "10"
  focal_point: "Bottom"
  preview_only: false

Куки не делают соединение надежным (рис. [-@fig:011]).

image:featured.png11
  caption: "11"
  focal_point: "Bottom"
  preview_only: false

Куки генерируются сервером(рис. [-@fig:012]).

image:featured.png12
  caption: "12"
  focal_point: "Bottom"
  preview_only: false

Куки бывают сессионные, удаляются при закрытии окна браузера (рис. [-@fig:013]).

image:featured.png13
  caption: "13"
  focal_point: "Bottom"
  preview_only: false

## Браузер TOR. Анонимизация

В луковой модели маршрутизации у нас тоже есть узлы. Они разделяются на охранный узел, промежуточный и выходной. В браузере Tor всегда есть три роутера, их не больше и не меньше (рис. [-@fig:014]).

image:featured.png14
  caption: "14"
  focal_point: "Bottom"
  preview_only: false

IP-адрес не должен быть известен охранному и промежуточному узлам (рис. [-@fig:015]).

image:featured.png15
  caption: "15"
  focal_point: "Bottom"
  preview_only: false

В анонимных сетях, таких как Tor, общий секретный ключ для сквозного шифрования требует участия всех трех типов узлов: охранного, промежуточного и выходного. Охранный узел сам по себе не обеспечивает генерацию ключа. Каждый узел вносит свой вклад в криптографический протокол (например, Diffie-Hellman), обеспечивая анонимность и защиту от перехвата. (рис. [-@fig:016]).

image:featured.png16
  caption: "16"
  focal_point: "Bottom"
  preview_only: false

Для получения пакетов не нужно использовать TOR. TOR — это технология, которая позволяет с некоторым успехом скрыть личность человека в интернете.(рис. [-@fig:017]).

image:featured.png17
  caption: "17"
  focal_point: "Bottom"
  preview_only: false

## Беспроводные сети Wi-fi

WiFi - это технология беспроводной локальной сети, она основана на стандарте IEEE 802.11 (рис. [-@fig:018]).

image:featured.png18
  caption: "18"
  focal_point: "Bottom"
  preview_only: false

WiFi работает на самом нижнем канальном уровне (рис. [-@fig:019]).

image:featured.png19
  caption: "19"
  focal_point: "Bottom"
  preview_only: false

WEP - устаревший и небезопасный метод шифрования WiFi из-за короткой длины ключа (40 бит), что делает его легко взламываемым. Использовать WEP категорически не рекомендуется.(рис. [-@fig:020]).

image:featured.png20
  caption: "20"
  focal_point: "Bottom"
  preview_only: false


Безопасность WiFi подразумевает защиту передачи данных между устройством (телефон, компьютер) и роутером (подключенным к интернету), осуществляемую с помощью шифрования и аутентификации.(рис. [-@fig:021]).

image:featured.png21
  caption: "21"
  focal_point: "Bottom"
  preview_only: false

WPA2 Personal предназначен для домашнего использования, а WPA2 Enterprise - для коммерческих организаций. (рис. [-@fig:022]).

image:featured.png22
  caption: "22"
  focal_point: "Bottom"
  preview_only: false


# Выводы

В результате выполнения блока "Безопасность в сети" я узнала, как работают сетевые пратаколы, куки-файлы, сети вайфай и для чего нужен браузер Tor.

