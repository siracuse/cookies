<?php
// si on appuie sur le bouton "Envoyer" alors
if (isset($_POST['insert'])) {
	//si les cookies 'fond' et 'texte' n'existe pas alors
	if (!isset($_COOKIE['fond']) and !isset($_COOKIE['texte'])) {
		$fond = $_POST['fond'];
		$texte = $_POST['texte'];
		$expir = time() + 60;
		setcookie("fond", $fond, $expir);
		setcookie("texte", $texte, $expir);
	} else {
		$fond = $_COOKIE['fond'];
		$texte = $_COOKIE['texte'];
	}
	//on rafraichit la page
	header('Refresh:0');
}

// si on appuie sur le bouton "Supprimer" alors
if (isset($_POST['delete'])) {
	if (isset($_COOKIE['fond']) and isset($_COOKIE['texte'])) {
		$expir = time() - 60;
		setcookie("fond", '', $expir);
		setcookie("texte", '', $expir);
	}
	header('Refresh:0');
}
?>

<!DOCTYPE html>
<html>

<head>
	<meta charset="UTF-8" />
	<title>Couleurs du site</title>
	<style type="text/css">
		body {
			background-color: <?php echo $_COOKIE['fond'] ?>;
			color: <?php echo $_COOKIE['texte'] ?>;
		}
	</style>
</head>

<body>
	<form method="post" action="">
		<fieldset>
			<legend>Choisissez vos couleurs (mot clé ou code)</legend> <br>

			<label for="fond">Couleur de fond</label>
			<input type="text" name="fond" id="fond" /><br><br>

			<label for="texte">Couleur de texte </label>
			<input type="text" name="texte" id="texte" /> <br><br>

			<input type="submit" value="Envoyer" name="insert" />
			<input type="submit" value="Supprimer" name="delete" />
		</fieldset>
	</form>
</body>

</html>
