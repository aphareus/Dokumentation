---
title: "Share rooms"
date: 2020-07-02T21:23:14+02:00
chapter: true
draft: false
weight: 40
---
# Share rooms and make them public
 {{% notice warning %}}
The share icon in the upper right corner of each room also provides a link, a QR code and various social networks. The link, however, leads to https://matrix.to/ from where you can access the room via an Element web app from https://element.io. In order to share a room within TU Dresden please use the methodes exlained in this artice.
 {{% /notice %}}
Every room has a socalled room-address, which can be found in the room settings under the submenu Advanced. A room address looks like this:

!aen6iekahv8Pi0zohf:tu-dresden.de

Because this cryptic address can not be read easily by humans, custom room addresses can be assigned. This is only necessary for rooms, which you want to make public and reference in other places.

Room addresses can either be globally published addresses (findable by users in other servers - useful for topics beyond the TU Dresden) or local addresses, which is only valid within the matrix home server at the TU Dresden.

For the more common case of the desired local address, click on "Show more" under Local Addresses in the room settings under the General tab:

![Room settings with the show more selected](/images/01_Sharing_en.png)

Afterwards a recognizable name of this room link can be assigned in the "Room alias" line (no spaces are allowed!):

![Room settings with the local addresses selected](/images/02_Sharing_en.png)

You can also assign different addresses. If the room address should be published in the room directory of the matrix home server of the TU Dresden, this can be done by the following. 

![room settings with the public room address selected](/images/03_Sharing_en.png)

The room address then has the following structure

#Room address name:tu-dresden.de

In a chat where you want to draw attention to this room, you can access a room with a local address by typing #roomaddress:tu-dresden.de. You also can create a hyperlink to the room, which you have to confirm with a mouse click.

Furthermore the assigned room address results in an internet address (URL):

https://matrix.tu-dresden.de/#/room/#roomaddress:tu-dresden.de

This can be easily distributed to the public or target group.

![share icon marked in the chat view of the room](/images/04_Sharing-Button_en.png)

{{% notice note %}}
The share icon at the top right of each room also offers a link, as well as a QR code and various social networks. This link leads to a page where you can select how the link should be opened. For example, the installed Element Client can be used, or it can be selected via which home server the room is to be entered. 
{{% /notice %}}

When you want to share a room within matrix, you can use the internal link feature by typing
```
#room_address:tu-dresden.de
```
Into the chat line. Automatic clickable completion suggestioins will be displayed. This is a special link within matrix, which will open directly in the client of the reciever.
