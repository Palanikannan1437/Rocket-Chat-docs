---
description: >-
  As a Rocket.Chat administrator, you can add, invite, activate or deactivate
  the guest users.
---

# Manage guest users

* [Guest Users in Rocket.Chat](manage-guest-users.md#guest-users-in-rocket.chat)&#x20;
* [Guest Access Permissions](manage-guest-users.md#rocket.chat-guest-access-permissions)&#x20;
* [Configure Guest Access](manage-guest-users.md#configure-guest-access-in-rocket.chat)
* [Add a guest user to channels](manage-guest-users.md#add-a-guest-user-to-channels)&#x20;
* [Invite a guest user](manage-guest-users.md#invite-a-guest-user)&#x20;
* [Enable guest users](manage-guest-users.md#enable-guest-users)&#x20;
* [Disable guest users](manage-guest-users.md#disable-guest-users)&#x20;

## Before you begin

You should be aware of the limitations set for guest users in Rocket.Chat.

{% hint style="info" %}
* Guest is a role.
* Guest is a role that is available just on Enterprise, and it's not possible to change the permissions for this role.
* All users assigned with the guest role, don't count on the cap of the seat, but they count towards the guest cap.
* It's possible to set a maximum number of guest users for every license.&#x20;
* It's possible to set a maximum number of channels a guest can join for every license
{% endhint %}

## Guest Users in Rocket.Chat

### What can a guest user do?

Guest users are anonymous users that want to write and participate in channels when the `Allow Anonymous Read` and `Allow Anonymous Write` settings are activated.

#### Guest users cannot:

{% hint style="info" %}
* create new channels, groups, or DMs;
* create personal access tokens;
* delete own messages;
* mention **all** and **here;**
* There isn’t a limitation on the number of free guest users.
{% endhint %}

## **Guest Access Permissions**

{% hint style="info" %}
Guest is a role that is available just on Enterprise, and it's not possible to change the permissions for this role.
{% endhint %}

Go to **Administration > Permissions.** You will notice that the permissions that a guest role has are: start the conversation, view direct messages, view joined the room, and view private room.

#### Permissions Available **for the Guest Role**

![Permissions](../../../../.gitbook/assets/GuestUser\_Permissions.png)

### Add a guest user to channels

To add a guest user, go to **Administration > Users > New** as shown below:

![](<../../../../.gitbook/assets/New User.png>)

Once the guest user is added, you will be able to edit, activate and deactivate the guest role.

### Invite a guest user

To invite a guest user, go to **Administration > Users > Invite** as shown below:

![](<../../../../.gitbook/assets/Invite Users.png>)

* Type the email address of the guest user that you want to invite to the channel.&#x20;
* Click **Add** and then add the guest user, which will then send an invitation to that email address inviting the user to be in the channels team.&#x20;

### Enable guest users

* Go to **User Info** and then click **Activate.**

![](../../../../.gitbook/assets/ActivateGuestuser.png)

### Disable guest users

* Go to **User Info** and then click **Deactivate.**

![](../../../../.gitbook/assets/Deactivateguest.png)
