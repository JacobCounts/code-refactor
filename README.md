# code-refactor

combined all css code with similar properties into a single class with the same styling 

changed html classes to reflect changes made in css 

example: css

.benefit {
    margin-bottom: 32px;
    color: #ffffff;
}
/*
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}
.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}
.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
*/

example: html

<div class="benefits">
        <div class="benefit">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>