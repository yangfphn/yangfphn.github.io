var quotes = [
		["晶巧在职员工总数", "2500人"],
		["晶巧大客户总数", "126个"],
		["晶巧已清理建筑物总数", "1200栋"],
		["晶巧广州室内工作地点数", "25处"],
		["晶巧成立年数", "5年"]
	].sort(function() {
		return 0.5 - Math.random();
	}), quoteIteration = 0, quoteIterationMax = quotes.length -1;

(function showQuotes() {
	if(quoteIteration >= quoteIterationMax) {
		quoteIteration = 0;
	} else {
		quoteIteration++;
	}
	var elem = document.getElementById("quotes");
	quotesHTML = "<p>&ldquo;" + quotes[quoteIteration][0] + "&rdquo; &mdash; <em>" + quotes[quoteIteration][1] + "</em></p>";
	elem.className = "fadeOut";
	setTimeout(function(){
		elem.innerHTML = quotesHTML;
		elem.className = "fadeIn";
	}, 3000);
	setTimeout(showQuotes, 10000);
})();
