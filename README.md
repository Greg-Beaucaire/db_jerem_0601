Les scripts SQL pour insérer les bouzins dans la DB : 

<p>INSERT INTO `mc` (`id`, `mc`) VALUES (NULL, 'mot_clé');</p>
<p>INSERT INTO `url` (`id`, `url`, `shortcut`, `datetime`, `description`) VALUES (NULL, 'url', 'url_courte', NOW(), 'description');</p>
<p>INSERT INTO `assoc_mc_url` (`id`, `mc_id`, `url_id`) VALUES (NULL, 'id_mot_clé', 'id_url');</p>
