# Accounts
list of accounts
setInterval(() => {
	var heart = document.querySelector('.coreSpriteHeartOpen');
	var arrow = document.querySelector('.coreSpriteRightPaginationArrow');
	if (heart) heart.click();
	arrow.click();
}, 10000);
