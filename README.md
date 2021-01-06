<h1>Les scripts SQL pour insérer les bouzins dans la DB</h1>

<p>Pour enter un nouveau mot-clé</p>
<p><b>INSERT INTO `mc` (`id`, `mc`) VALUES (NULL, 'mot_clé');</b></p><br>

<p>Pour enter une nouvelle url</p>
<p><b>INSERT INTO `url` (`id`, `url`, `shortcut`, `datetime`, `description`) VALUES (NULL, 'url', 'url_courte', NOW(), 'description');</b></p><br>

<p>Pour lier une url à un mot-clé</p>
<p><b>INSERT INTO `assoc_mc_url` (`id`, `mc_id`, `url_id`) VALUES (NULL, 'id_mot_clé', 'id_url');</b></p>
