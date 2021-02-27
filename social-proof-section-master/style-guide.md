# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Very Dark Magenta: hsl(300, 43%, 22%)
Soft Pink: hsl(333, 80%, 67%)

### Neutral

Dark Grayish Magenta: hsl(303, 10%, 53%)
Light Grayish Magenta: hsl(300, 24%, 96%)
White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Spartan](https://fonts.google.com/specimen/Spartan)
- Weights: 400, 500, 700













.container-bottom {
	display: grid;
	grid-template-columns: repeat(3, 365px);
	grid-gap: 26px;
	width: 80vw;
	height: 40vh;
	margin: 100px;
	margin-top: -80px;
}

h3 {
	color: #fff;
}
.usuario-1, .usuario-2, .usuario-3 {
	background-color: rgb(81,31,80);
	border-radius: 3%;
}

.container-usuarios-top {
	display: grid;
	grid-template-columns: 100px 1fr;
	grid-template-rows: 40px 40px;
	grid-template-areas: 
	"foto titulo"
	"foto subtitulo";
}

.container-usuarios-top img {
	margin: 10px;
	border-radius: 50%;
	grid-area: foto;
	width: 70px;

}
.container-usuarios-top h3 {
	grid-area: titulo;
	font-size: 1em;
	align-self: end;
	background: red;
}

.container-usuarios-top b {
	grid-area: subtitulo;
	color: rgb(145,85,137);
	align-self: start;
	background-color: blue;
	font-size: .9em;
}






























.container {
    width: 80%;
    max-width: 1440px;
    margin: 0 auto;
}

.top {
    display: flex;
    justify-content: space-between;
    padding-top: 50px;
    flex-wrap: wrap;
}

.top h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.top p {
    font-size: .9rem;
}

.customer-rating {
    display: flex;
    flex-wrap: wrap;
    background-color: #F7F2F8;
    padding: .7rem 1.5rem;
    margin-bottom: .8rem;
    font-size: .7rem;
    font-weight: 400;
    align-items: center;
    border-radius: 10px;
}

.ratings-img {
    margin-right: 1rem;
}

.rating-2nd {
    margin-left: 2rem;
}

.rating-3rd {
    margin-left: 4rem;
}

.bottom-rating {
    margin-top: 50px;
}

.rating-card {
    display: flex;
    justify-content: space-between;
    
}
    
.card {
    width: 300px;
    height: 150px;
    background-color: #511F50 ;
    margin-right: 1rem;
    padding: 20px 15px;
    border-radius: 8px;
}

.profile {
    display: flex;
    align-items: center;
    
}

.profile img {
    width: 50px;
    height: auto;
    border-radius: 100px;
    margin-right: 1rem;
}

.profile h3 {
    font-size: .7rem;
    color: #fff;
    margin-bottom: 3px;
}

.profile h5{
    font-size: .6em;
    color: rgb(134, 126, 126);
}

.review {
    display: flex;
    justify-content: center;
}

.review p {
    font-size: .7rem;
    color:  #FFF0FF;
    margin-top: 10px;
    font-weight: 500;
    line-height: 1.1rem;
}

.rating-card-2 {
    margin-top: 1rem;
}

.rating-card-3 {
    margin-top: 2rem;
}

.bottom {
    background-image: url("/images/bg-pattern-bottom-desktop.svg");
    background-repeat: no-repeat;
    background-position: right;
}

@media (max-width: 800px) {
    .top h1 {
        font-size: 2rem;
        margin-bottom: 1rem;
        text-align: center;
    }
    .top p {
        font-size: 1rem;
        text-align: center;
        margin-bottom: 20px;
    }
    .rating-2nd {
        margin-left: 0;
    }
    .rating-3rd {
        margin-left: 0;
    }
    .ratings-img {
        margin-right: 0;
    }
    .customer-rating  {
        justify-content: center;
    }
    .rating-card {
        justify-content: center;
        flex-wrap: wrap;
        margin: 0;
    }
    .card {
        width: 100%;
        margin-top: 1rem;
        
    }

    .bottom-rating  {
        margin-top: 0;
        margin-bottom: 1rem;
    }
}