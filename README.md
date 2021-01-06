<h1>Les scripts SQL pour insérer les bouzins dans la DB</h1>

<p>Pour enter un nouveau mot-clé</p>
<p>INSERT INTO `mc` (`id`, `mc`) VALUES (NULL, 'mot_clé');</p><br>

<p>Pour enter une nouvelle url</p>
<p>INSERT INTO `url` (`id`, `url`, `shortcut`, `datetime`, `description`) VALUES (NULL, 'url', 'url_courte', NOW(), 'description');</p><br>

<p>Pour lier une url à un mot-clé</p>
<p>INSERT INTO `assoc_mc_url` (`id`, `mc_id`, `url_id`) VALUES (NULL, 'id_mot_clé', 'id_url');</p>
