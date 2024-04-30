let cards = ["c1", "c2", "c3", "c4","c5","c6","c7"];
cards.forEach(function (cardId) {
    let card = document.querySelector("." + cardId);
    card.addEventListener("click", function () {
        console.log("Card " + cardId + " clicked");
        expand(cardId);
    });
});

function expand(cardId) {
    let prevCard = document.querySelector(".expand");
    console.log(prevCard);
    if (prevCard != null) {
        prevCard.classList.remove("expand");
        prevCard.classList.add("fold");
        
    }
        let card = document.querySelector("." + cardId);
        card.classList.add("expand");
        if(cardId==(cards.lengh-1)){
            card.classList.remove("expand");
            card.classList.add("fold"); 
        }
    }