---
title: {{ title }}
date: {{ date }}
---
<% for (var link in site.data.chairs) { %>
  <a href="<%= site.data.chairs[link].url %>"> <%= link %> from <%= site.data.chairs[link].university %></a> <%= site.data.chairs[link].email %>
<% } %>