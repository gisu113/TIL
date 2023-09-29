-ランキングの表示方法
<ul>
  <% @rankings.each_with_index do |post, index| %>
    <li>
      <span><%= index + 1 %>位</span>
      <%= link_to post.hobby, post_path(post) %>
      <span>いいね数: <%= post.likes.count %></span>
    </li>
  <% end %>
</ul>
