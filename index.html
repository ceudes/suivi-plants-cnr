<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SNS-CNR Bénin</title>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<style>
body { font-family: Arial, sans-serif; padding: 20px; background: #f4f4f4; }
h1 { color: #0066cc; text-align: center; }
table { width: 100%; border-collapse: collapse; margin: 15px 0; background: white; }
th, td { border: 1px solid #ccc; padding: 8px; }
th { background: #0066cc; color: white; }
</style>
</head>
<body>
<h1>🌱 SNS-CNR Bénin</h1>
<div id="content">Chargement...</div>

<script>
const supabase = Supabase.createClient(
'https://ton-url.supabase.co',
'ta-cle-anon-publique'
);

async function loadCommunes() {
const { data } = await supabase.from('communes').select('*');
document.getElementById('content').innerHTML = '<pre>' + JSON.stringify(data, null, 2) + '</pre>';
}

loadCommunes();
</script>
</body>
</html>


Le ven. 3 juil. 2026 à 10:21, Corneille Kakanakou <corneillekakanakou@gmail.com> a écrit :
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SNS-CNR Bénin</title>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<style>
body { font-family: Arial, sans-serif; padding: 20px; background: #f4f4f4; }
h1 { color: #0066cc; }
.tab { padding: 10px; background: #ddd; display: inline-block; margin: 5px; cursor: pointer; }
.tab.active { background: #0066cc; color: white; }
table { width: 100%; border-collapse: collapse; margin: 15px 0; background: white; }
th, td { border: 1px solid #ccc; padding: 8px; }
th { background: #0066cc; color: white; }
</style>
</head>
<body>
<h1>🌱 SNS-CNR Bénin - Suivi National des Plants</h1>
<div id="tabs"></div>
<div id="content"></div>

<script>
const supabaseUrl = 'https://ton-url-supabase.supabase.co';
const supabaseKey = 'ta-cle-publique-supabase';
const supabase = Supabase.createClient(supabaseUrl, supabaseKey);

// Remplace avec tes vraies valeurs Supabase (URL et clé publique)
// Tu les trouves dans Supabase → Settings → API

async function loadCommunes() {
const { data } = await supabase.from('communes').select('*');
console.log(data);
}

loadCommunes();
</script>
</body>
</html>


Le ven. 3 juil. 2026 à 10:00, Corneille Kakanakou <corneillekakanakou@gmail.com> a écrit :
-- Table Production (si elle n'existe pas)
CREATE TABLE IF NOT EXISTS production_plants (
id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
commune_id UUID REFERENCES communes(id),
nom_pepinieriste TEXT,
production_totale INTEGER,
tectona INTEGER,
gmelina INTEGER,
eucalyptus INTEGER,
acacia INTEGER,
khaya INTEGER,
terminalia INTEGER,
ceiba INTEGER,
autres_essences TEXT,
date_production DATE,
created_at TIMESTAMP DEFAULT NOW()
);

-- Table Enlèvement
CREATE TABLE IF NOT EXISTS enlevement_plants (
id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
commune_id UUID REFERENCES communes(id),
proprietaire TEXT,
quantite_produite INTEGER,
quantite_enlevee INTEGER,
date_enlevement DATE,
created_at TIMESTAMP DEFAULT NOW()
);

-- Table Mise en Terre
CREATE TABLE IF NOT EXISTS mise_en_terre (

id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
commune_id UUID REFERENCES communes(id),
village TEXT,
proprietaire TEXT,
espece TEXT,
nombre_plants INTEGER,
superficie_ha NUMERIC,
date_mise DATE,
created_at TIMESTAMP DEFAULT NOW()
);


Le jeu. 2 juil. 2026 à 21:21, Corneille Kakanakou <corneillekakanakou@gmail.com> a écrit :
-- Table Communes
CREATE TABLE communes (
id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
nom TEXT NOT NULL,
departement TEXT,
code TEXT,
latitude NUMERIC,
longitude NUMERIC,
created_at TIMESTAMP DEFAULT NOW()
);

-- Table Production
CREATE TABLE production_plants (
id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
commune_id UUID REFERENCES communes(id),
nom_pepinieriste TEXT,
production_totale INTEGER,
tectona INTEGER,
gmelina INTEGER,
eucalyptus INTEGER,
acacia INTEGER,
khaya INTEGER,
terminalia INTEGER,
ceiba INTEGER,
autres_essences TEXT,
date_production DATE,
created_at TIMESTAMP DEFAULT NOW()
);

-- Table Enlèvement
CREATE TABLE enlevement_plants (
id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
commune_id UUID REFERENCES communes(id),
proprietaire TEXT,
quantite_produite INTEGER,
quantite_enlevee INTEGER,
date_enlevement DATE,
created_at TIMESTAMP DEFAULT NOW()
);

-- Table Mise en Terre
CREATE TABLE mise_en_terre (
id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
commune_id UUID REFERENCES communes(id),
village TEXT,
proprietaire TEXT,
espece TEXT,
nombre_plants INTEGER,
superficie_ha NUMERIC,
date_mise DATE,
created_at TIMESTAMP DEFAULT NOW()
);
