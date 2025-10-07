[Meine erlebnise über Mobing und wie ich da rausgekommen bin.zip](https://github.com/user-attachments/files/22751101/Meine.erlebnise.uber.Mobing.und.wie.ich.da.rausgekommen.bin.zip)

<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Erfahrungen über Mobing und wie man das alles verhindern kann!</title>
            <!-- Firebase SDKs einbinden -->
            <script src="https://www.gstatic.com/firebasejs/10.7.0/firebase-app.js"></script>
            <script src="https://www.gstatic.com/firebasejs/10.7.0/firebase-auth.js"></script>
            <script src="https://www.gstatic.com/firebasejs/10.7.0/firebase-firestore.js"></script>
          
</head>
<!-- Im <head> für CSS -->
<link rel="stylesheet" href="styles.css">

<!-- Am Ende des <body> für JS -->
<script src="script.js"></script>

<body>
    <div id="menu">
    <button onclick="show('erfahrungen')">Meine Erfahrungen</button>
    <button onclick="show('tipps')">Tipps gegen Mobbing</button>
    <button onclick="show('hilfe')">Hilfe & Unterstützung</button>
</div>

<div id="content">
    <h2 id="title">Wilkommen!</h2>
    <div id="main">Wähle Links eine Kategorie aus, um mehr zu erfahren.</div>
    


</body>
</html>

# new file style.css
function show(section) {
    const title = document.getElementById("title");
    const main  = document.getElementById("main");

    if(section === "erfahrungen") {
        title.innerText = "Meine Erfahrungen über Mobbing";
        main.innerHTML = `
            <p>🌧️ Keys Geschichte – Der Weg durch das Mobbing.</p>
            <p>
Mein Name ist Key und bin 15 Jahre alt.
Früher wurde ich oft wegen meines Aussehens gemobbt. Ich habe thailändische Wurzeln – mein Papa kommt aus Thailand – und darauf bin ich heute stolz.
Aber damals war das nicht leicht.

An der Herrenbachschule wurde ich oft ausgelacht und beleidigt.
Manche Kinder nannten mich „Chinese“ oder sagten „Chin chon chun“, nur wegen meiner Augen.
Sie zogen an ihren Augen und machten sich über mich lustig.
Ich versuchte stark zu bleiben, aber jedes Mal tat es weh – tief im Inneren.

Einmal packten mich ältere Schüler an meiner Kapuze, trugen mich über den Schulhof und stellten sich im Kreis um mich herum.
Sie lachten. Ich stand in der Mitte, konnte mich nicht bewegen, und mein Herz schlug so laut, dass ich es fast hören konnte.
Ich wollte weglaufen, aber ich konnte nicht. Ich fühlte mich klein, allein und machtlos.

Zuhause habe ich dann mit meinen Eltern gesprochen.
Mein Papa sagte leise:

„Key, sei stolz auf dich. Du bist Thailänder – und das ist etwas Schönes. Deine Wurzeln machen dich einzigartig.“

Und meine Mama nahm mich in den Arm und sagte:

„Lass dir nie einreden, dass du weniger wert bist. Du bist unser Sohn, und du bist stark. Die, die dich ärgern, verstehen einfach nicht, was Respekt bedeutet.“

Diese Worte haben mir Mut gegeben.

Als ich später an die Pankratiusschule kam, war ich unsicher. Ich hatte Angst, dass alles wieder von vorne losgeht.
Aber ich traf neue Menschen – freundliche Menschen.

Was mir besonders geholfen hat, mein Selbstbewusstsein zu stärken, war Kickboxen und Fitness. Durch den Sport habe ich gelernt, an mich zu glauben, mich zu verteidigen und stolz auf meinen Körper und meine Leistung zu sein. Das Training hat mir Kraft und Selbstvertrauen gegeben, und ich habe gemerkt, wie ich immer stärker und sicherer wurde.

Und langsam begann ich, wieder zu lachen, zu vertrauen, zu glauben, dass ich gut bin, so wie ich bin.

Heute weiß ich:
Mobbing hat nichts mit dem Opfer zu tun. Es zeigt nur, wie unsicher die sind, die mobben.
Ich habe gelernt, aufrecht zu stehen – stolz auf meine Familie, auf meine Herkunft, und auf mich selbst. 🇹🇭

Wenn ich jetzt jemanden sehe, der ausgelacht oder ausgeschlossen wird, erinnere ich mich an mein früheres Ich.
Und ich helfe.
Denn niemand sollte sich schämen müssen, anders zu sein.

Jeder Mensch ist wertvoll – auch du. 💛.</p>
        `;
    } else if(section === "tipps") {
        title.innerText = "Tipps gegen Mobbing";
        main.innerHTML = `
            <ul>
                <li>Sprich mit jemandem, dem du vertraust.</li>
                <li>Bleib ruhig und lass dich nicht provozieren.</li>
                <li>Dokumentiere Vorfälle.</li>
                <li>Suche Unterstützung bei Lehrern oder Eltern.</li>
                <li>Vermeide Orte, an denen du dich unsicher fühlst.</li>
                <li>Stärke dein Selbstbewusstsein durch Hobbys und Freunde.</li>
                <li>Erinnere dich: Du bist wertvoll und nicht allein.</li>
                <li>Mache Sport, dass hilft oft sehr z.b. KickBoxen, Fitnis, Fußball, Vollybal ... , wie du siehst gibt es viele moglichkeiten die du machen kannst um dein Selbstbewusstsein zu stärken.</li>
            </ul>
        `;
    } else if(section === "hilfe") {
        title.innerText = "Hilfe & Unterstützung ";
        main.innerHTML = `
            <p>Man kann Lehrer oder Eltern informieren, sich Hilfe holen oder...</p>
        `;
    }  
}  
