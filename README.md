<h1>Les scripts SQL pour insérer les bouzins dans la DB</h1>

<pre><p>Pour enter un nouveau mot-clé</p>
<code>INSERT INTO `mc` (`id`, `mc`) VALUES (NULL, 'mot_clé');</code><br></pre>

<pre><p>Pour enter une nouvelle url</p>
<code>INSERT INTO `url` (`id`, `url`, `shortcut`, `datetime`, `description`) VALUES (NULL, 'url', 'url_courte', NOW(), 'description');</code><br></pre>

<pre><p>Pour lier une url à un mot-clé</p>
<code>INSERT INTO `assoc_mc_url` (`id`, `mc_id`, `url_id`) VALUES (NULL, 'id_mot_clé', 'id_url');</code></pre>
