## SYSTEM SCUMMVM ##
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
ROM files extensions accepted: .scummvm

There are only 2 steps involved in setting up a scummvm game.

1) Populate the required files for a game in its own folder and name the folder with a ".scummvm" extension.
2) Create a text file in the game's folder with a ".scummvm" extension and save the Game ID in the text file (case sensitive).

The value inside your .scummvm text file should be the full GAME ID according to the below list, including the colon.

The above instructions are the easiest and recommended way to load the game in RCADE, but RCADE will still try and automatically detect and run games in a few different ways to try and be as compatible as possible.

IMPORTANT REMINDER: Game IDs are case sensitive.

For example, setting up the game "Versailles 1685" (reference the below list):
- Create a game folder named "Versailles 1685.scummvm" (This name/extension is optional, but recommended)
- Populate this folder with all the files needed to run the game
- Create a text file in the game folder called "versailles.scummvm"
- Inside the versailles.scummvm text file, type this (without the quotes): "cryomni3d:versailles"
  (If you do not do this, RCADE will *try* to figure it out automatically)

RCADE also supports running the text file directly instead of the folder, so if you don't name the folder with a scummvm extension then you can launch the game from the scummvm text file inside the folder.


Game ID                        Full Title                                                 
------------------------------ -----------------------------------------------------------
scumm:atlantis                 Indiana Jones and the Fate of Atlantis
scumm:indy3                    Indiana Jones and the Last Crusade
scumm:loom                     Loom
scumm:maniac                   Maniac Mansion
scumm:monkey                   The Secret of Monkey Island
scumm:monkey2                  Monkey Island 2: LeChuck's Revenge
scumm:pass                     Passport to Adventure
scumm:samnmax                  Sam & Max Hit the Road
scumm:tentacle                 Day of the Tentacle
scumm:zak                      Zak McKracken and the Alien Mindbenders
scumm:indyloom                 Indiana Jones and the Last Crusade & Loom
scumm:indyzak                  Indiana Jones and the Last Crusade & Zak McKracken
scumm:zakloom                  Zak McKracken & Loom
scumm:ft                       Full Throttle
scumm:dig                      The Dig
scumm:comi                     The Curse of Monkey Island
scumm:activity                 Putt-Putt & Fatty Bear's Activity Pack
scumm:brstorm                  Bear Stormin'
scumm:fbear                    Fatty Bear's Birthday Surprise
scumm:fbpack                   Fatty Bear's Fun Pack
scumm:funpack                  Putt-Putt's Fun Pack
scumm:puttmoon                 Putt-Putt Goes to the Moon
scumm:puttputt                 Putt-Putt Joins the Parade
scumm:arttime                  Blue's Art Time Activities
scumm:baseball2001             Backyard Baseball 2001
scumm:Baseball2003             Backyard Baseball 2003
scumm:basketball               Backyard Basketball
scumm:football2002             Backyard Football 2002
scumm:freddicove               Freddi Fish 5: The Case of the Creature of Coral Cove
scumm:moonbase                 Moonbase Commander
scumm:pjgames                  Pajama Sam: Games to Play on Any Day
scumm:readtime                 Blue's Reading Time Activities
scumm:Soccer2004               Backyard Soccer 2004
scumm:SoccerMLS                Backyard Soccer MLS Edition
scumm:spyozon                  SPY Fox 3: Operation Ozone
scumm:airport                  Let's Explore the Airport with Buzzy
scumm:balloon                  Putt-Putt and Pep's Balloon-O-Rama
scumm:baseball                 Backyard Baseball
scumm:Blues123Time             Blue's 123 Time Activities
scumm:BluesABCTime             Blue's ABC Time Activities
scumm:BluesBirthday            Blue's Birthday Adventure
scumm:BluesTreasureHunt        Blue's Treasure Hunt
scumm:catalog                  Humongous Interactive Catalog
scumm:chase                    SPY Fox in Cheese Chase
scumm:dog                      Putt-Putt and Pep's Dog on a Stick
scumm:farm                     Let's Explore the Farm with Buzzy
scumm:football                 Backyard Football
scumm:freddi                   Freddi Fish 1: The Case of the Missing Kelp Seeds
scumm:freddi2                  Freddi Fish 2: The Case of the Haunted Schoolhouse
scumm:freddi3                  Freddi Fish 3: The Case of the Stolen Conch Shell
scumm:freddi4                  Freddi Fish 4: The Case of the Hogfish Rustlers of Briny Gulch
scumm:FreddisFunShop           Freddi Fish's One-Stop Fun Shop
scumm:jungle                   Let's Explore the Jungle with Buzzy
scumm:lost                     Pajama Sam's Lost & Found
scumm:maze                     Freddi Fish and Luther's Maze Madness
scumm:mustard                  SPY Fox in Hold the Mustard
scumm:pajama                   Pajama Sam 1: No Need to Hide When It's Dark Outside
scumm:pajama2                  Pajama Sam 2: Thunder and Lightning Aren't so Frightening
scumm:pajama3                  Pajama Sam 3: You Are What You Eat From Your Head to Your Feet
scumm:puttcircus               Putt-Putt Joins the Circus
scumm:puttrace                 Putt-Putt Enters the Race
scumm:PuttsFunShop             Putt-Putt's One-Stop Fun Shop
scumm:putttime                 Putt-Putt Travels Through Time
scumm:puttzoo                  Putt-Putt Saves the Zoo
scumm:SamsFunShop              Pajama Sam's One-Stop Fun Shop
scumm:soccer                   Backyard Soccer
scumm:socks                    Pajama Sam's Sock Works
scumm:spyfox                   SPY Fox 1: Dry Cereal
scumm:spyfox2                  SPY Fox 2: Some Assembly Required
scumm:thinker1                 Big Thinkers First Grade
scumm:thinkerk                 Big Thinkers Kindergarten
scumm:water                    Freddi Fish and Luther's Water Worries
access:amazon                  Amazon: Guardians of Eden
access:martian                 Martian Memorandum
adl:hires0                     Hi-Res Adventure #0: Mission Asteroid
adl:hires1                     Hi-Res Adventure #1: Mystery House
adl:hires2                     Hi-Res Adventure #2: Wizard and the Princess
adl:hires3                     Hi-Res Adventure #3: Cranston Manor
adl:hires4                     Hi-Res Adventure #4: Ulysses and the Golden Fleece
adl:hires5                     Hi-Res Adventure #5: Time Zone
adl:hires6                     Hi-Res Adventure #6: The Dark Crystal
agi:agi                        Sierra AGI game
agi:agi-fanmade                Fanmade AGI game
agi:agidemo                    AGI Demo
agi:bc                         The Black Cauldron
agi:caitlyn                    Caitlyn's Destiny
agi:ddp                        Donald Duck's Playground
agi:goldrush                   Gold Rush!
agi:kq1                        King's Quest I: Quest for the Crown
agi:kq2                        King's Quest II: Romancing the Throne
agi:kq3                        King's Quest III: To Heir Is Human
agi:kq4                        King's Quest IV: The Perils of Rosella
agi:lsl1                       Leisure Suit Larry in the Land of the Lounge Lizards
agi:mickey                     Mickey's Space Adventure
agi:mixedup                    Mixed-Up Mother Goose
agi:mh1                        Manhunter 1: New York
agi:mh2                        Manhunter 2: San Francisco
agi:pq1                        Police Quest I: In Pursuit of the Death Angel
agi:serguei1                   Serguei's Destiny 1
agi:serguei2                   Serguei's Destiny 2
agi:sq0                        Space Quest 0: Replicated
agi:sq1                        Space Quest I: The Sarien Encounter
agi:sq2                        Space Quest II: Vohaul's Revenge
agi:sqx                        Space Quest: The Lost Chapter
agi:tetris                     AGI Tetris
agi:troll                      Troll's Tale
agi:winnie                     Winnie the Pooh in the Hundred Acre Wood
agi:xmascard                   Xmas Card
agos:pn                        Personal Nightmare
agos:elvira1                   Elvira - Mistress of the Dark
agos:elvira2                   Elvira II - The Jaws of Cerberus
agos:waxworks                  Waxworks
agos:simon1                    Simon the Sorcerer 1
agos:simon2                    Simon the Sorcerer 2
agos:feeble                    The Feeble Files
agos:dimp                      Demon in my Pocket
agos:jumble                    Jumble
agos:puzzle                    NoPatience
agos:swampy                    Swampy Adventures
ags:ags                        Adventure Game Studio Game
ags:ags-scan                   AGS Game Scanner
ags:6da                        The 6 Day Assassin
ags:aaronsepicjourney          Aaron's Epic Journey
ags:aceduswell                 Ace Duswell: Where's The Ace?
ags:achristmastale             A Christmas Tale
ags:adayinthefuture            A Day In The Future
ags:adventuregame              Adventure Game
ags:adventurenoir              Adventure Noir
ags:agsbgeditor                AGS Background Editor
ags:aliengame                  Alien Game
ags:anotherrpg                 Another RPG
ags:asapadventure              ASAP Adventure
ags:bertthenewsreader          Bert the Newsreader
ags:billybobwildnight          Billy Bob's Wild Night
ags:blackjack                  AGS Blackjack
ags:blastoff                   Blastoff!
ags:bluecupontherun            Bluecup on the Run
ags:bobsquest2                 Bob's Quest 2: The quest for the AGS Blue cup award
ags:bookofspells1              The Book of Spells (A funtasy Adventure) - Chapter 1
ags:bookofspells2              The Book of Spells (A funtasy Adventure) - Chapter 2
ags:bookofspells3              The Book of Spells (A funtasy Adventure) - Chapter 3
ags:calsoon                    Calsoon
ags:candy                      I Want Candy
ags:captainmuchly              Captain Muchly Drinks Bleach
ags:carverisland1              The Secret of Carver Island
ags:carverisland2              Carver Island 2: Mrs. Rodriguez's Revenge
ags:castlequest                Castle Quest
ags:chef                       The Chef
ags:commanderkeenron           Commander Keen Enters Reality-on-the-Norm
ags:compensation               Compensation
ags:cosmos                     Cosmos
ags:crimetime                  Crime Time
ags:cutlass                    Cutlass
ags:damnthatspill              Clyde Remolen in: Damn that Spill!
ags:darksects                  Dark Sects
ags:davyjonescestmort          Davy Jones c'est Mort
ags:davyjonesisback            Davy Jones is Back
ags:deepbright                 Deepbright
ags:defenderofron              Defender of Reality-on-the-Norm
ags:defsrpgdemo                Def's RPG Demo
ags:demonslayer1               DemonSlayer 1: Bert the Super Demon Slayer Guy
ags:demonslayer2               DemonSlayer 2: DemonSlayer vs. Vegetable Vampires
ags:demonslayer3               DemonSlayer 3: Hotel and Alley
ags:demonslayer4               DemonSlayer 4
ags:dirkchafberg               Dirk Chafberg
ags:dogkennel                  The Dog Kennel
ags:domjohnson                 Dom Johnson
ags:earwigisangry              Earwig Is Angry!
ags:edgeofreality              Edge of Reality
ags:edsgravedigger             Ed's Gravedigger
ags:elburro                    El Burro
ags:equallyinsane              Jake Rabbit in: E.I. - Equally Insane
ags:erniesbigadventure1        Ernie's Big Adventure
ags:erniesbigadventure2        Ernie's Big Adventure II
ags:everythingeuro             Everything Euro / Alles Euro
ags:exile                      Exile
ags:exodus                     Exodus
ags:eyesofthejadesphinx        Eyes of the Jade Sphinx
ags:faddevil                   Fad of Devil's Hash
ags:fatman                     Fatman
ags:firewall                   Firewall
ags:floyd                      Floyd SB the Company Man
ags:fowlplay                   Reality-on-the-Norm 2 and 1/2: Fowl Play
ags:gaeafallen                 Gaea Fallen
ags:gorthor                    Gorthor of the Cave People
ags:grandfathertreasure        Grandfather's Treasure
ags:grannyzombiekiller         Granny Zombiekiller in: Mittens Murder Mystery
ags:gregsmountainousadventure  Greg's Mountainous Adventure
ags:greysgreytadv              Mr. Grey's Greyt Adventure
ags:helmsuntitled              Helm's Untitled Game
ags:henkkaquest                Henkka: Mini Quest
ags:hermit                     Night of the Hermit
ags:hiphendrix                 Highly Hip Hendrix
ags:hookymcp                   Hooky McPegleg, Pirate Postman
ags:housequest                 Joe Jenkins in: House Quest
ags:huckleburyhippie           Hucklebury Hippie
ags:ijuntitled                 Ian James' Untitled Game
ags:inadream                   In a Dream
ags:indygoldmedallion          Indiana Jones and The Gold Medallion
ags:indyguybrush               Indiana Jones - Alla ricerca di Guybrush Threepwood
ags:indysecretchamber          Indiana Jones and the Secret Chamber of Schloss Brunwald
ags:intergalacticlife          Intergalactic Life
ags:invasionspacealiens        Invasion of the Space Aliens Who Are Not From Earth But From Some Other Planet
ags:islandquest                Island Quest
ags:ispy                       I Spy
ags:jamesbondage               James Bondage
ags:javajo                     Java Jo's Koffee Stand!
ags:jinglebells                Jingle Bells
ags:kidnapped                  Kidnapped
ags:kittensandcacti            Kittens and Cacti
ags:larryvales1                Larry Vales: Traffic Division
ags:larryvales2                Larry Vales II: Dead Girls are Easy
ags:larryvales3                Larry Vales III: Time Heals All 'Burns
ags:lassiandrogerventure       Lassi and Roger Venture a Bit
ags:lassiandrogermeetgod       Lassi and Roger Meet God
ags:lassiquest1                Lassi's Quest I
ags:lassiquest1remake          Lassi's Quest I Remake
ags:lassiquest2                Lassi's Quest II
ags:leisuresuitlarry4          Leisure Suit Larry 4
ags:limpyghost                 Limpy Ghost
ags:littlejonnyevil            Little Jonny Evil
ags:littlewillydarts           Little Willy's Darts Game
ags:littlewillyshotgun         Little Willy's Shotgun Fun Zone!
ags:lorryloader                Lorry Loader
ags:losttreasureron            The Lost Treasure of Reality-on-the-Norm
ags:ludwig                     VonLudwig
ags:lunchtimeofthedamned       Lunchtime Of The Damned
ags:lupoinutile                Lupo Inutile
ags:magsceremony2001jul        July 2001 MAGS Ceremony
ags:magsceremony2001jun        June 2001 MAGS Ceremony
ags:martychonks                Marty Chonks in: Dances With Camels
ags:maxdark                    Max the Dark Hero
ags:meninbrown                 Men in Brown
ags:miagsremake                Monkey Island AGS Remake
ags:midtownshootout            Mid-Town Shoot-Out
ags:migaiden                   Monkey Island Gaiden
ags:mikasdream                 Mika's Surreal Dream
ags:mojoisland                 Mojo Island
ags:momsquest                  Mom's Quest
ags:monkeypeninsula            The Treasure of Monkey Peninsula
ags:monkeyplank                Monkey Plank
ags:moosewars                  Moose Wars: Desire For More Cows
ags:murder                     Murder
ags:murderfishhotel            Philip Illinilings and the Murder at Fish Hotel
ags:nicholaswolfe1             Nicholas Wolfe part I: Framed
ags:nightoftheplumber          Night of the Plumber
ags:nightwatchron              Nightwatch (2001)
ags:nihilism                   Nihilism
ags:nomedon                    Nomedon Inc.
ags:notanothersq               Not Another Space Quest
ags:novomestro                 Novo Mestro
ags:odysseus                   The Trials of Odysseus Kent
ags:oldparkquest               Old Park Quest
ags:orbblanc                   Orb Blanc: Ball of the Universe
ags:pantaloon                  Quirk Pantaloon
ags:paranormality              Lee & Perrin: Paranormality
ags:pd                         P.D.
ags:permanentdaylight          Permanent Daylight
ags:perpetrator                Perpetrator
ags:pezzobertrum               Pezzo Bertrum and the Band That Wouldn't Die
ags:piratefry1                 Pirate Fry and Volcano Island
ags:pixelypete                 Pixely Pete
ags:pizzaquest                 Pizza Quest
ags:pointblank                 Point Blank
ags:pornquest                  Porn Quest
ags:postmanonlydiesonce        The Postman Only Dies Once
ags:preachersjump              Preachers Can't Jump
ags:projectevilspy             Project Evilspy: FenderQ Meets Jeeforce for Lunch
ags:qfc                        Quest For Colours
ags:qfg412                     Quest for Glory 4 1/2
ags:raymondskeys               Raymond's Keys: A Tragedy
ags:redflagg                   Red Flagg in: Don't Call Me Blue!
ags:returnofdvs                Return of Die Vie Ess
ags:richardlonghurst           Richard Longhurst and the Box That Ate Time
ags:ripp                       Revenge in Parelly Point
ags:robblanc1                  Rob Blanc I: Better Days of a Defender of the Universe
ags:robblanc2                  Rob Blanc II: Planet of the Pasteurised Pestilence
ags:robblanc3                  Rob Blanc III: The Temporal Terrorists
ags:rodekill                   Rode Kill: A Day In the Life
ags:rodequest                  Rode Quest
ags:ronbeachparty              Reality-on-the-Norm Beach Party
ags:ronxmas2002                Reality-on-the-Norm Xmas 2002
ags:samthepiratemonkey         Sam The Pirate Monkey
ags:short                      Short
ags:slackerquest               Slacker Quest
ags:sma1                       Second Moon Adventure - Part I: Night
ags:snailquest1                Snail Quest
ags:snailquest2                Snail Quest 2
ags:snailquest3                Snail Quest 3
ags:sol                        Sol
ags:southpark                  South Park
ags:sovietunionstrikesback     The Soviet Union Strikes Back
ags:space                      Space
ags:spacemail                  Space Mail
ags:startreksnw                Star Trek Explorer: Strange New World
ags:startrektng                Star Trek: The Next Generation
ags:stickmen                   Stickmen
ags:superdisk                  Superdisk
ags:teamwork                   Teamwork Tutorial
ags:testicle                   Day of the Testicle
ags:thecrownofgold             The Crown of Gold
ags:theinexperiencedassassin   Petrakov: The Inexperienced Assassin
ags:theisland                  The Island
ags:thetower                   The Tower
ags:thevestibule               The Vestibule
ags:thewarp                    The Warp
ags:tinygreen                  Tiny Green Piece of Crap
ags:tommato                    Tom Mato's Grand Wing-Ding
ags:tullesworld1               Tulle's World 1: The Roving of Candale
ags:tullesworld3               Tulle's World 3: The Glorious Realm of Thendor
ags:tvquest                    TV Quest
ags:ultimerr                   Ultimerr XXII: The Gems of Anthrax
ags:universalequalizer         The Universal Equalizer
ags:vengeanceofthechicken      Vengeance of the Chicken
ags:waitkey                    WaitKey();
ags:whokilledkennyrogers       Who killed Kenny Rogers?
ags:zakagsremake               Zak McKracken and the Alien Mindbenders AGS Remake
ags:3geeks                     3 GEEKS
ags:aboardtheadventure         Aboard the Adventure
ags:alemmo                     Al Emmo And The Lost Dutchman's Mine
ags:alemmoanozira              Al Emmo's Postcards from Anozira
ags:alum                       Alum
ags:apotheosis                 The Apotheosis Project
ags:astroloco                  Astroloco: Worst Contact
ags:atotk                      A Tale Of Two Kingdoms
ags:avcsurvivalguide           AVC's Survival Guide / Guía de supervivencia en CAV
ags:beer                       Beer!
ags:beyondowlsgard             Beyond the Edge of Owlsgard
ags:blackwell1                 The Blackwell Legacy
ags:blackwell2                 Blackwell Unbound
ags:blackwell3                 The Blackwell Convergence
ags:blackwell4                 The Blackwell Deception
ags:blackwell5                 The Blackwell Epiphany
ags:captaindisaster            Captain Disaster in: Death Has A Million Stomping Boots
ags:captainhook                Captain Hook and the Lost Girl
ags:castledornstein            Castle Dornstein
ags:charnelhousetrilogy        The Charnel House Trilogy
ags:chronicleofinnsmouth       Chronicle of Innsmouth
ags:crimsondiamond             The Crimson Diamond
ags:crystalshardadventurebundle Crystal Shard Adventure Bundle
ags:danewguys2                 Da New Guys: Day of the Jackass
ags:detectivegallo             Detective Gallo
ags:diamondsintherough         Diamonds in the Rough
ags:docapocalypse              Doc Apocalypse
ags:downfall2009               Downfall (2009)
ags:downfall2016               Downfall (2016)
ags:dreamswitchhouse           Dreams in the Witch House
ags:dustbowl                   Dustbowl
ags:excavationhb               The Excavation at Hob's Barrow
ags:falconcity                 Falcon City
ags:feriadarles                Feria d'Arles
ags:footballgame               Football Game
ags:geminirue                  Gemini Rue
ags:ghostdream                 Ghostdream
ags:ghostman                   Ghostman: The Council Calamity
ags:goldenwake                 A Golden Wake
ags:graceward                  Graceward
ags:grandmabadass              GrandMa Badass
ags:guardduty                  Guard Duty
ags:herdiscoming               Herd is Coming
ags:incantamentum              Incantamentum
ags:insectophobiaep1           Insectophobia: Episode 1
ags:jorry                      JORRY
ags:justignorethem             Just Ignore Them
ags:justignorethembrea1        Just Ignore Them: Brea's Story Tape 1
ags:kathyrain                  Kathy Rain
ags:killyourself               Kill Yourself
ags:lamplightcity              Lamplight City
ags:lancelothangover           Lancelot's Hangover
ags:larrylotter                Larry Lotter and the Test of Time / Warthogs
ags:lastdayadolf               The Last Day of Adolf
ags:lastpirateadventure        The Last Pirate Adventure: Drake's Treasure
ags:legendofhand               Legend of Hand
ags:mage                       Mage's Initiation: Reign of the Elements
ags:metaldead                  Metal Dead
ags:mountainsofmadness         Chronicle of Innsmouth: Mountains of Madness
ags:mybigsister                My Big Sister
ags:nellycootalot-hd           Nelly Cootalot: Spoonbeaks Ahoy! HD
ags:neofeud                    Neofeud
ags:odissea                    Odissea - An Almost True Story
ags:oott                       Order of the Thorne: The King's Challenge
ags:perfecttides               Perfect Tides
ags:perfidiouspetrolstation    The Perfidious Petrol Station
ags:phantomfellows             The Phantom Fellows
ags:primordia                  Primordia
ags:projectorface              Projector Face
ags:qfi                        Quest for Infamy
ags:quantumnauts               Quantumnauts
ags:quantumnauts2              Quantumnauts 2
ags:redbow                     Red Bow
ags:resonance                  Resonance
ags:richardandalice            Richard & Alice
ags:rnrneverdies               Rock 'n' Roll Will Never Die!
ags:roguestate                 Rogue State
ags:samaritan                  The Samaritan Paradox
ags:shardlight                 Shardlight
ags:shivah                     The Shivah
ags:shoaly                     Shoaly You Can't Be Serious!
ags:sisterssecret              Sisters' Secret
ags:smallsister                Small Sister
ags:snowproblem                Snow Problem
ags:spaceraven                 Space raven quest - Tiny planet
ags:sphonx                     Sphonx
ags:starshipquasar             Starship Quasar
ags:stayingalive               The Ancient Art of Staying Alive
ags:strangeland                Strangeland
ags:sulifallenharmony          Suli Fallen Harmony
ags:sumatra                    Sumatra: Fate of Yandi
ags:superjazzman               Super Jazz Man
ags:symploke1                  Symploke: Legend of Gustavo Bueno (Chapter 1)
ags:symploke2                  Symploke: Legend of Gustavo Bueno (Chapter 2)
ags:symploke3                  Symploke: Legend of Gustavo Bueno (Chapter 3)
ags:tales                      Tales
ags:technobabylon              Technobabylon
ags:theadventuresoffatman      The Adventures of Fatman
ags:theantidote                The Antidote
ags:thebeardinthemirror        The Beard in the Mirror
ags:thecastle                  The Castle
ags:thecatlady                 The Cat Lady
ags:theropods                  Theropods
ags:thesecretofhuttongrammarschoolvga The Secret of Hutton Grammar School VGA
ags:thesecretsofjesus          The Secrets of Jesus
ags:theterribleoldman          The Terrible Old Man
ags:timegentlemenplease        Time Gentlemen, Please!
ags:unavowed                   Unavowed
ags:untilihaveyou              Until I Have You
ags:waitingfortheloop          Waiting For the Loop
ags:welcometosunnymunarvagir   Welcome to Sunny Munarvagir
ags:whispersofamachine         Whispers of a Machine
ags:wingman                    WingMan
ags:wolfterritory              Wolf Territory
ags:yetilastescape             The Last Escape of Yeti
ags:zniwadventure              Zniw Adventure
ags:onironauta                 Onironauta
ags:kq1agdi                    King's Quest I: Quest for the Crown Remake
ags:kq2agdi                    King's Quest II: Romancing the Stones Remake
ags:kq3agdi                    King's Quest III Redux: To Heir is Human
ags:qfg2agdi                   Quest for Glory II: Trial by Fire Remake
ags:sq2fg                      Space Quest for Glory
ags:sq2vga                     Space Quest II - Vohaul's Revenge VGA Remake
ags:kq3vga                     King's Quest III: To Heir is Human VGA Remake
ags:10waysfromsunday           10 Ways from Sunday
ags:11-11-11                   11-11-11
ags:12hoursslave               12 Hours a Slave
ags:15minutes                  15 Minutes
ags:1dayamosquito              1 day a mosquito
ags:2034acaftercanada1         2034 A.C. (After Canada)
ags:2034acaftercanada2         2034 A.C. (After Canada) II
ags:24hours                    24 Hours
ags:30minutes                  30 minutes
ags:3pigsandawolf              Three Little Pigs and a Wolf
ags:46memorylane               46 Memory Lane
ags:4lungboy                   4-Lung Boy
ags:4ofclubs                   4 of Clubs
ags:5daysastranger             5 Days A Stranger
ags:5oclocklock                5-O'clock Lock
ags:6174solitaire              6174 Solitaire
ags:6daysasacrifice            6 Days A Sacrifice
ags:6mornings                  6mornings
ags:7daysaskeptic              7 Days A Skeptic
ags:99species                  99 Species
ags:9hourstodawn               9 Hours to Dawn
ags:9monthsin                  9 Months In
ags:aazor                      Aazor: Life of a Demon - Part I: The Beginning
ags:abducted10mins             Abducted: 10 Minutes!!!
ags:abduction                  Abduction
ags:abettermousetrap           A Better Mouse Trap
ags:ablemabel                  Able Mabel gets a Job
ags:abominationobtainer        Abomination Obtainer
ags:abscission                 Abscission
ags:absent                     Absent
ags:absentpart1                Absent - Part I: Innocent Until Proven Guilty
ags:absin                      Absin - An Interactive Mystery
ags:absurdistan                Absurdistan
ags:acaixa                     A caixa
ags:acatsnight1                A Cat's Night
ags:acatsnight2                A Cat's Night 2 - Orazio Goes To Town
ags:access                     _Access
ags:aceking                    Ace King
ags:acequest                   Ace Quest
ags:acharchronicles            Achar Chronicles: Oblitus
ags:achristmasblunder          A Christmas Blunder
ags:achristmasghost            A Christmas Ghost
ags:achristmasnightmare        A Christmas Nightmare
ags:achristmaswish             A Christmas Wish
ags:aciddd                     AciDDD
ags:acjadventure               A Christopher Jones Adventure
ags:acureforthecommoncold      A Cure for the Common Cold
ags:acuriouspastime            A Curious Pastime
ags:acurioussilence            A Curious Silence
ags:adalinepicnic              Adaline and the Moon Picnic
ags:adateinthepark             A Date in the Park
ags:adaywithmichael            A Day with Michael
ags:advallinthegame            Adventure: All In The Game
ags:advbunnybunnyman           Adventures of Bunny Bunnyman / Pupu Pupulaisen Seikkailut
ags:adventureisland            Adventure Island
ags:adventurequest             Adventure Quest
ags:adventurequest2            Adventure Quest 2 - Winterlong
ags:adventuresofjoshanddyan    The Adventures of Josh and Dyan
ags:adventuresofmaxfaxepisode1 Adventures of Max Fax (episode 1)
ags:adventuretheinsidejob      Adventure: The Inside Job
ags:adventureworld             Adventure's World
ags:advwelcome                 Adventure: Welcome to the Genre
ags:aerinde                    Aerinde
ags:aeronuts                   AeroNuts
ags:aeternaduel                Aeterna Duel
ags:affairoftheweirdo          Affair of the Weirdo
ags:affection                  Affection
ags:afragmentofher             A Fragment of Her
ags:afriendindeed              A Friend Indeed ...
ags:afrojones                  Afro Jones
ags:afterashadow               After a Shadow
ags:agentbee                   Agent Bee
ags:agenthudson                Agent Hudson
ags:agenttrinityepisode0theultimatum Agent Trinity - Episode 0 - The Ultimatum
ags:aggghost                   A G-G-Ghost!
ags:agitprop                   Agitprop: The Game
ags:agnosticchicken            The Agnostic Chicken: The Quest For The Bottle Opener
ags:agsawards2008              AGS Awards Ceremony 2008
ags:agsawards2016              AGS Awards Ceremony 2016
ags:agsawards2017              AGS Awards Ceremony 2017
ags:agsawards2020              AGS Awards Ceremony 2020
ags:agsawardsbp                AGS Awards Backstage Pass
ags:agscamerastd               AGS Cameras Tech Demo
ags:agschess                   AGS Chess
ags:agscolosseum               AGS Colosseum
ags:agsdarts                   AGS 180 Darts
ags:agsdarts2                  AGS 180 Darts 2
ags:agsfightgame2009           Ahmet's AGS Fight Game 2009
ags:agsfightgameremix          Ahmet's AGS Fight Game Remix
ags:agsfootballer              AGS Footballer
ags:agsinvaders                AGS-Invaders
ags:agsjukebox                 AGS JukeBox
ags:agslife                    AGSLife
ags:agsmagus                   AGS Magus
ags:agsmastermind              AGS Mastermind
ags:agsmittensshooter          AGS Mittens Shooter
ags:agsmoduletester            AGS Module Tester
ags:agswerewolf                AGS Werewolf
ags:agsyahtzee                 AGS Yahtzee
ags:agsyahtzee2                AGS Yahtzee 2
ags:agunshotinroom37           A Gunshot in Room 37
ags:ahomieadventure            A Homie Adventure
ags:aidaschristmas             Aida's Strange Christmas
ags:aidashalloween             Aida's Bizarre Halloween
ags:ainthegoffantabulousw      Adventures in the Galaxy of Fantabulous Wonderment
ags:airwaveifoughtthelawandthelawone ~airwave~ - I Fought the Law, And the Law One
ags:alandlordsdream            A Landlord's Dream
ags:alansaveschristmas         Alan saves Christmas (and most of the world too)
ags:aliceinwonderlandis        Lewis Carroll's Alice In Wonderland - an interactive storybook
ags:alienattack                Alien Attack
ags:aliencarniage              Alien Carniage
ags:aliencowrampage            Alien Cow Rampage: Orion Needs Your Milk!
ags:alienescapade              Alien Escapade
ags:alienpuzzleinvasion        Alien Puzzle Invasion
ags:alienrapeescape            Alien Rape Escape
ags:alienspaceman              The Alien / The Spaceman
ags:alienthreat                Alien Threat
ags:alientimezone              Alien Time Zone
ags:allgonesoon                All Gone Soon
ags:allgonesoon2               All Gone Soon 2
ags:allhallowseve              All Hallows' Eve
ags:allpigs                    All Pigs Deserve To Burn In Hell
ags:allthewaydown              All The Way Down
ags:alluminum                  P.I. Al Luminum: Haunted House
ags:almostblue                 Almost Blue
ags:aloneinthenight            Alone in the Night
ags:alphabeta                  Alphabeta: A Room Full of Words
ags:alphablock                 AlphaBlock
ags:alphadog                   Alpha Dog
ags:alphax                     Alpha X
ags:alphaxsmash                Alpha X - Project: Smash
ags:alquest1                   Al-Quest 1
ags:alysvsthephantomfelinefoe  Alys vs. The Phantom Feline Foe
ags:amagicstone                A magic stone
ags:america2000                America 2000
ags:amotospuf                  Amoto's Puf
ags:amongthorns                Among Thorns
ags:amtag                      AMTAG: another medieval themed adventure game
ags:amused                     A-Mused
ags:analienswork               An Alien's Work Is Never Done...
ags:ancientaliens              Ancient Aliens - The Roots of Sound
ags:anentertainingspeech       An Entertaining Speech
ags:aneternityreflecting       An Eternity, Reflecting
ags:anightinberry              A night in Berry / Une nuit en Berry
ags:anightmareonduckburg       A Nightmare on Duckburg
ags:anightthatwouldntend       A Night That Wouldn't End
ags:anighttoremember           A Night to Remember
ags:animalagency               Animal Agency
ags:animalcruelty              Animal Cruelty
ags:anna                       anna
ags:annaquest                  Anna's Quest Vol. 1: Winfriede's Tower
ags:annieandroidautomatedaffection Annie Android: Automated Affection
ags:anoffer                    An offer you cannot refuse
ags:anotherhero                Another Hero
ags:anothermuseum              Another Museum
ags:anotherwayout              Another Way Out
ags:anthonysessay              Anthony's Essay
ags:anticipatingmurder         Anticipating Murder
ags:antiheroes                 Anti-Heroes
ags:anxiousawakening           An Anxious Awakening
ags:apiratestale               A pirates tale
ags:aplaceinthesun             A Place In The Sun
ags:aplacewithoutfrontier      A Place Without Frontier
ags:apocalypsemeow1            Apocalypse Meow Chapter 1 - Gatitos: The Paws of Fate
ags:apocalypsevel              Apocalypse: Vel
ags:applefarm                  Apple Farm
ags:appointmentwithdeath       Appointment With Death
ags:apprentice                 Apprentice
ags:apprentice2                Apprentice II: The Knight's Move
ags:aprofoundjourney           A Profound Journey
ags:apunkwithwheels            A punk with wheels
ags:aractaur                   Aractaur
ags:araindogstory              A Raindog Story
ags:archeos                    Archeos
ags:ardensvale                 Arden's Vale
ags:ardentfever                Ardent Fever
ags:arewethereyet              Are we there yet?
ags:arjunaz78                  Arjunaz78 @ AGS
ags:aroomwithoutyou            A Room Without You In It
ags:armageddonmargaret         Armageddon Margaret
ags:artofdying                 The Art of Dying
ags:asecondface                A Second Face: The Eye of Geltz is Watching You
ags:ashinaredwitch             Ashina: The Red Witch
ags:ashpines                   Ash Pines
ags:ashortnightmare            A Short Nightmare
ags:asimplefix                 A Simple Fix
ags:asledmundo                 ASL: Edmundo with music
ags:asporia                    Asporia: Hidden Threat
ags:asterix                    Asterix and the Roman Underground
ags:astranded                  Astranded (Astro-Stranded)
ags:astron                     Astron
ags:asuspiciousdate            A Suspicious Date
ags:aswinsdream                Aswin's Dream
ags:ataintedtreat              A Tainted Treat
ags:ataleinthezoo              A Tale in the Zoo
ags:ataleofbetrayal            A Tale Of Betrayal
ags:atapi                      Atapi
ags:athingaboutnothingness     A thing about nothingness
ags:atotkjukebox               A Tale of Two Kingdoms Jukebox
ags:atreatandsometricks        A Treat and Some Tricks
ags:attackgame                 Attack Game
ags:atthecafe                  At the Café
ags:audioquest                 Audio Quest
ags:aunaturel                  Au Naturel
ags:automation                 Automation
ags:averyspecialdog            A very special dog
ags:awakener                   Awakener
ags:awakening                  Awakening - Part 1: Escape
ags:awakeningofthesphinx       Awakening of the Sphinx
ags:awalkindatomb              A walk in da tomb
ags:awalkinthepark             A Walk in the Park
ags:awayinatower               Away in a Tower
ags:awesmoequest               Awesmoe Quest
ags:awkward                    Ok...Now this is awkward!
ags:awomanforallseasons        A Woman for All Seasons
ags:axmasevetale               A Xmas Eve Tale
ags:bachelorstory              Bachelor Story
ags:backdoorman                Back Door Man
ags:backlot                    Backlot: Adventure Antics
ags:badbunker                  Bad Bunker
ags:badluck                    Bad Luck
ags:bakeoffitalia              Bake Off Italia - The Graphic Adventure
ags:baldysadventure            Baldy's Adventure
ags:balloonface                Balloon Face
ags:baltazarthefamiliar        Baltazar the Familiar
ags:bananaman                  Banana Man
ags:bananaracer                Banana Racer
ags:barahir                    Barahir's Adventure: Askar's Castle
ags:barelyfloating             Barely Floating
ags:barhoppers                 BarHoppers
ags:barndilemma                Barn Dilemma
ags:barnrunner1p1              Barn Runner 1: The Armageddon Eclair (Part 1)
ags:barnrunner1p2              Barn Runner 1: The Armageddon Eclair (Part 2)
ags:barnrunner3                Barn Runner 3: Don't Jerk The Trigger of Love
ags:barnrunner4                Barn Runner 4: The Prick Who Came In From the Cold
ags:barnrunner5p1              Barn Runner 5: The Forever Friday (Part 1)
ags:barnrunner5p2              Barn Runner 5: The Forever Friday (Part 2)
ags:barnrunner5p3              Barn Runner 5: The Forever Friday (Part 3)
ags:barnrunnerbake1            Barn Runner Bake Sale 1: The Rich Dame Who Cut The Cheese
ags:barnrunnerhall1            Barn Runner Halloween 1: Fully Automatic Mojo
ags:barnrunnervalentine1       Barn Runner Valentine 1: Pucker Factor
ags:barnrunnervn1              Barn Runner Visual Novel 1: The Mayor's New Dress
ags:barnrunnerxmas0            Barn Runner Xmas 0: Christmas Soup
ags:barnrunnerxmas2            Barn Runner Xmas 2: Wreck The Halls
ags:barrier                    Barrier
ags:barrunner                  Ed Watts: Bar Runner
ags:bartolomeo                 Bartolomeo, misled by circumstances, learns that appearances can be deceptive
ags:bartsquestfortv            Bart's Quest For TV
ags:battlewarriorsrt           Battle Warriors: Rovendale Tactics
ags:bbcscreensaver             Background Blitz Collection Screensaver
ags:bcremake                   Black Cauldron Remake
ags:beacon                     Beacon
ags:bear                       Bear Story
ags:beardychin                 Old Woman Beardychin and the Scruffedy Bumtious
ags:bearinvenice               Bear in Venice
ags:beasts                     Beasts
ags:beatthebuzzer              Beat the Buzzer
ags:beautiesandbeasts          Beauties and Beasts
ags:beforethedarkcrystal2      Before the Dark Crystal II
ags:beforeww2                  Before WW2
ags:bellyofthebeast            Belly of the Beast
ags:belowzero                  Below Zero
ags:belusebiusarrival          Belusebius Arrival
ags:benchandlerpi              Ben Chandler: Paranormal Investigator!
ags:bentheredanthat            Ben There, Dan That!
ags:beprepared                 Be Prepared / Bodi Pripravljen
ags:berthabuttsboogie          Bertha Butt's Boogie
ags:besieged                   BESIEGED, Or: How to Get Out of A Castle... Without Being Catapulted
ags:bestowersofeternity        Bestowers of Eternity - Part One
ags:betrayal                   Betrayal
ags:betweenpillars             Between the Pillars of Creation
ags:beyondeternity1            Beyond Eternity - episode 1: The West College Disappearances
ags:beyondhorizon              Beyond Horizon
ags:beyondreality              Beyond Reality
ags:beyondterror               Beyond Terror
ags:beyondthedoor              Beyond the door
ags:beyondthehorizon           Beyond the horizon
ags:bicschristmastale          Bic's Christmas Tale
ags:bigbadwolf3lilpiggies      The Big Bad Wolf & Three little pigs
ags:bigblue                    Big Blue World Domination
ags:bigfoot                    Bigfoot
ags:bigglesonmars              Biggles On Mars
ags:bigtroubleinlittleimola    Big Trouble in Little Imola
ags:billybstar                 Billy B. Star and the Lapaset Travel Quest
ags:billyboysimportantwinelottery Billy Boy's Important Wine Lottery
ags:billygoatsgruff            Billy Goats Gruff
ags:billymasterswasright       Billy Masters Was Right
ags:billythekid                The New Adventures Of Billy The Kid
ags:bioluminescence            Bioluminescence
ags:bird                       bird
ags:birdsandbees               Of birds and bees
ags:birdybirdy                 Birdy Birdy
ags:bitstream                  Bitstream
ags:bittersweet                Bittersweet
ags:biwa                       Biwa of Blood
ags:bizarreearthquake          Bizarre Earthquake
ags:bjcase1                    Ben Jordan P.I. Case 1: In Search of the Skunk-Ape
ags:bjcase2                    Ben Jordan P.I. Case 2: The Lost Galleon of the Salton Sea
ags:bjcase3                    Ben Jordan P.I. Case 3: The Sorceress of Smailholm
ags:bjcase4                    Ben Jordan P.I. Case 4: Horror at Number 50
ags:bjcase5                    Ben Jordan P.I. Case 5: Land of the Rising Dead
ags:bjcase6                    Ben Jordan P.I. Case 6: Scourge of the Sea People
ags:bjcase7                    Ben Jordan P.I. Case 7: The Cardinal Sins
ags:bjcase8                    Ben Jordan P.I. Case 8: Relics of the Past
ags:bjpww1                     Ben Jordan P.W.W. Case 1: Wrath of the Skunk Ape
ags:blackbirdstrikesback       The Blackbird Strikes Back
ags:blackfriday                Black Friday
ags:blackhandgang              The Adventures of the Black Hand Gang
ags:blackmailinbrooklyn        Blackmail in Brooklyn
ags:blackmorph                 Black Morph
ags:blacksect1                 Black Sect Remake
ags:blacksect2                 Black Sect 2: The Cursed Crypt - Remake
ags:blackudder                 Blackudder: To Doubloon or not to Doubloon
ags:bladespassion              Blades of Passion: An Oceanspirit Dennis Adventure
ags:blazeos                    Blaze From Outer Space
ags:blindsweeper               BlindSweeper
ags:blindtosiberia             Blind to Siberia
ags:blitheep1                  Blithe - Episode 1: The quiet town
ags:blockz                     Blockz - A Slider Puzzle Game
ags:bloodedfields              Blooded Fields
ags:bluelobe                   Blue Lobe Inc.
ags:bluemoon                   Blue Moon
ags:boardquest                 Board Quest
ags:bob                        Bob
ags:bobescapes                 Bob Escapes / Bob En Cavale
ags:bobgoeshome                Bob Goes Home
ags:bobgoeshomedeluxe          Bob Goes Home Deluxe
ags:bobsquest1                 Bob's Quest
ags:bogsadventure              Bog's Adventures in the Underworld
ags:bogsadventureineasy3d      Bog's Adventure in Easy3D
ags:bohemianyard               Bohemian Yard
ags:boilerroom                 Boiler Room Blues
ags:boltaction                 Bolt Action
ags:bone                       Bone
ags:boogiebum                  Boogie Bum's Roger Quest
ags:bookofdestiny              Book of Destiny
ags:bookofspells4              The Book of Spells (A funtasy Adventure) - Chapter 4
ags:bookofspellscomplete       The Book of Spells (A funtasy Adventure)
ags:bookunfinished             The Book Unfinished
ags:bovinebyproduct            Bovine By-Product
ags:bowanddork                 Bow and Dork
ags:bowserquirkquest           Bowser Quirk Quest
ags:box                        Box
ags:boxfight                   Boxfight for AGS
ags:boxland                    Think Outside the Boxland
ags:boyindahood                Boy in da hood: Give me the money!
ags:bradbradsonkeyquest        Brad Bradson: Key Quest
ags:braquagegringotts          Braquage à Gringotts
ags:breakage                   Breakage
ags:breakdown                  Breakdown
ags:breakingcharacter          Breaking Character
ags:breakfastont1              Breakfast on Trappist-1
ags:brokenwindows1             Broken Windows - Chapter 1
ags:brokenwindows2             Broken Windows - Chapter 2
ags:brokenwindows3             Broken Windows - Chapter 3
ags:brotherswreckers           Brothers & Wreckers
ags:brotherswreckersep7        Brothers & Wreckers - Episode 7
ags:brucequest                 Bruce Quest: The Secrets of the Outback
ags:bruises                    Bruises
ags:bsg78                      BSG78 - Unexpected at the Rising Star
ags:bubblewrap                 Bubble Wrap Popping Simulator 2013
ags:bubsybobcat                Bubsy The Bobcat In Rip Van Bubsy Starring Bubsy
ags:buccaneer                  Buccaneer
ags:bullettrain                Bullet Train
ags:bunawantsbeer              Buna Wants Beer
ags:bunnyquest                 Bunny Quest
ags:burrow                     Burrow
ags:burymeinthesand            Bury Me in the Sand
ags:bustinthebastille          Bustin' the Bastille
ags:butcherstanys              Butcher Stanys
ags:butcherstanys2             Butcher Stanys II: Stanys Meets Marilyn Manson
ags:byohero                    BYO-Hero
ags:bythenumbers               By the Numbers
ags:bytheswordconspiracy       By the Sword: Conspiracy
ags:byzantine                  Byzantine
ags:cabbagequest               Cabbage Quest
ags:cabbagesandkings           Cabbages and Kings
ags:cachoquest                 Cacho Quest
ags:calebsdrunkenadventure     Caleb's Drunken Adventure
ags:calequest                  Cale Quest
ags:callmegeorge1              Call Me George, Chapter 1: Prophecy
ags:calsoon2                   Calsoon 2
ags:calvin                     Calvin
ags:camp1                      Camp 1
ags:campaigndaphnewhite        The Campaign of Daphne White
ags:candlecove                 Return to Candle Cove
ags:candyforest                The Candy Forest
ags:capricorn                  Tropic of Capricorn
ags:captaincringe              Chronicles of Captain Cringe
ags:captaindisastermoon        Captain Disaster In: The Dark Side of the Moon
ags:captaindownes              Captain Downes and the Pirate Princess
ags:captainskull               The Astonishing Captain Skull
ags:carrotbobinzxspeccyworld   Carrot Bob in ZX Spectrum world
ags:cartenstein                Cartenstein
ags:cartlife                   Cart Life
ags:casablancathedayafter      Casablanca, The Day After
ags:casenoir                   Case Noir
ags:caseofthefestivalfilcher   The Case of the Festival Filcher
ags:caseofthemuffindiver       The case of The Muffin Diver
ags:cassandra                  Cassandra
ags:castleescapech1            Castle Escape - Chapter 1
ags:castleescapech2            Castle Escape - Chapter 2
ags:castleoffire               Castle of Fire
ags:catacombic                 Catacombic
ags:catapault                  CATapault
ags:catking                    Long Live the Cat King
ags:cauche                     Cauchemarionto
ags:caverns                    Caverns
ags:caveofavarice              Cave of Avarice
ags:cayannepepper              Cayanne Pepper
ags:cedricandtherevolution     Cedric and the Revolution
ags:cedricshooter              Cedric Shooter
ags:ceelo                      Cee-Lo!
ags:celestialcatastrophe       Danny Sexbang in Celestial Catastrophe
ags:celticchaosep1             Celtic Chaos Episode 1: Cold mead
ags:celticchaosep2             Celtic Chaos Episode 2: Fishermen's fiends
ags:cgascreensaver             CGA Games Screensaver
ags:chaelle1                   Chaëlle chapitre 1 : Mission Dragon
ags:chaelle2                   Chaëlle chapitre 2 : Chimérie
ags:chaelle3                   Chaëlle chapitre 3 : La Bataille de Zahrasie
ags:chalkman                   Chalkman
ags:chalksquest                Chalk's Quest
ags:challengetentacle          Challenge of the Tentacle
ags:chanceofthedead            Chance Of The Dead
ags:charamba1                  Charamba, Chapter 1: Bitches in the Desert
ags:charamba2                  Charamba, Chapter 2: Hallowe'en
ags:charliefoxtrot             Charlie Foxtrot and The Galaxy of Tomorrow
ags:chasingrobot               Chasing Robot
ags:chatroom                   Chatroom
ags:cheerfulscience            Cheerful Science
ags:chekken                    cheKKen
ags:cherrysquest               Cherry's Quest For Coffee
ags:chessboard                 ChessBoard
ags:chezapa                    Chez Apa
ags:chickchaser                Chick Chaser
ags:chicken                    Chicken
ags:chickenfraction            Chicken Fraction
ags:chickenvsroad              Chicken vs. Road
ags:chinesecheckers            Chinese Checkers
ags:chlorinde                  White Bear Beauty Chlorinde and the Paranormal Parrot
ags:chocofrogs                 ChocoFrogs
ags:chongoadv                  Chongo's China Adventure
ags:chriscolumbus              Christopher Columbus is an Idiot
ags:christmas42                Christmas42
ags:christmasgamearcade        CGA: Christmas Game Arcade
ags:christmashunt              Christmas Hunt
ags:christmaspresent           Search for the Christmas Present - Remake
ags:christmasquest             Christmas Quest
ags:christmasquest2            Christmas Quest 2: The Yuletide Flows In
ags:christmasquest3            Christmas Quest 3: Santa's Little Help Desk
ags:cirquedezale               Cirque de Zale
ags:city                       City
ags:cityofthieves              City of Thieves: Rescue Sandy
ags:citythatdrowned            The City That Drowned
ags:claire                     Claire
ags:clarinette                 Clarinette
ags:classnotes                 Class Notes
ags:clik                       Clik
ags:clipgoestotown             Clip goes to town
ags:clockworklabyrinth         The Clockwork Labyrinth
ags:clotildesoffritti          Clotilde Soffritti in: Never Buy a Used Spaceship
ags:clotildesoffritti2         Clotilde Soffritti in: Never Double Park your Spaceship
ags:clownatthecircus           Clown at the Circus
ags:clubmidget                 Club Midget
ags:clubofevil                 Club of Evil
ags:coderbattle                CODERBATTLE - quest for the whole game -
ags:coelldeckaflight           Coell Decka Flight
ags:coinopafternoon            Coin-Operated Afternoon
ags:coinrush2                  Coin Rush 2
ags:colaskunk                  Cola Skunkette: A Bit of Cleanup
ags:coldhandreef               The Cold Hand Reef
ags:coldmeat                   Cold Meat
ags:coldstorage                Cold Storage
ags:colinsimpson               Colin Simpson Leaves Employment
ags:colonelcarver              Colonel Carver's Carnival Curios
ags:colourclash                Colour Clash
ags:colourwise                 ColourWise
ags:colourwiseleveleditor      ColourWise - Level Editor
ags:columbuslander             Columbus Lander
ags:comedyquest                Comedy Quest
ags:cometcollision             Comet Collision
ags:comiclassic                The Curse of Monkey Island: Classic Edition
ags:commandoadv                Commando: The Adventure Game
ags:comradecitizenpart1        Comrade Citizen - Part I
ags:concurrence                Concurrence
ags:confessionsofacatburglar   Confessions Of A Cat Burglar
ags:confinement                Confinement
ags:coniferskunks              Conifer Skunks: Osvald's Surprise
ags:conspiracybelowzero        Conspiracy: Below-Zero
ags:conspiracyofsongo          Conspiracy of Songo
ags:constancethebarbarian      Constance the Barbarian
ags:contact                    Contact
ags:content                    Content
ags:contrapasso                Commissar's Contrapasso
ags:cop                        Cop
ags:corneliuschristmas         Cornelius Cat in: How the Cat Saved Christmas
ags:corneliuspest              Cornelius Cat in: The Uncontrollable Pest
ags:cornersshiny               Corner's Shiny (2013 edition)
ags:cosmodyssey                Cosmodyssey: Jammy Edition
ags:cosmospuzzle               Cosmos Puzzle
ags:cosmosquest1               Cosmos Quest I
ags:cosmosquest2               Cosmos Quest II
ags:cosmosquest3               Cosmos Quest III
ags:cougarsquestforfreedom     Cougar's Quest for Freedom
ags:counterfeit                Counterfeit
ags:coupdecup                  Coup de Cup
ags:coyote1                    Coyote Episode I: The Mexican
ags:crackwell1                 The Crackwell Legacy
ags:crackwell2                 Crackwell Unhinged
ags:craftofevil                Craft Of Evil
ags:crankosaurus               Crankosaurus Prime and the Blue Crystal Pursuit
ags:crankosaurusff             Crankosaurus Prime and the Blue Crystal Pursuit: The Fangs of Fortune
ags:crashcourse                Crash Course
ags:crashedalien               The Story Of The Alien That Crashed
ags:crashevadedestroy          Crash! Evade! Destroy!
ags:crave                      Crave
ags:crepefields                Crepe Fields: A Scare Among Crows
ags:crimezone                  Crime Zone
ags:criminalist                Criminalist
ags:crimmsson                  Crimm's Son
ags:crossstitch                Cross Stitch Casper
ags:crowandfoxy                Crow and Foxy / Le Corbeau et la Renarde
ags:crowcawled                 A Crow Cawled Raven
ags:cryo                       Cryo
ags:crypt                      Crypt
ags:cryptic                    Cryptic
ags:crystalball                The Crystal Ball
ags:crystalquest               Crystal Quest
ags:csihunt1                   CSI Hunt 1
ags:cspb                       Cake & Smurphy Puzzle Battle!
ags:cursevampire               The Curse of the Vampire
ags:cutman                     Cutman
ags:cyberjack                  cyberJACK
ags:cybermemory                Cybermemory Not Found
ags:cyberpunk97ep1             Cyberpunk '97 - Episode 1
ags:daceyinthedark             Dacey in the Dark: Prelude
ags:dada                       Dada: Stagnation in Blue
ags:dadaxmas                   Dada Christmas Special: Stagnation in Red and White
ags:daggerhell                 DAGGERHELL
ags:dakota                     Dakota
ags:daleks                     Daleks
ags:dalesfilmquest             Dale's Film Quest
ags:damsel                     Damsel - Chapter 1: Stress on the Tress
ags:dancetilyoudrop            Dance Til' You Drop!
ags:danewguys                  Da New Guys
ags:dangermouse                Danger Mouse
ags:dangerousderek             Dangerous Derek's Livestream
ags:dangerouslandsrt2          Dangerous Lands: Rovendale Tactics 2
ags:dannydreadisoncall         Danny Dread is On Call
ags:dantesday                  Dante's Day
ags:darkblack                  Dark Black
ags:darkforce                  DarkForce: Peace Among Nations
ags:darkofnight                Dark of Night
ags:darktimesmerrychristmas    Dark Times (Merry Christmas)
ags:darum                      Darum
ags:davegeneric                Dave Generic
ags:davidletterman             David Letterman - the Video Game
ags:davyjonesspellbook         Davy Jones' Spellbook
ags:dawnswonderedatagesend     Dawns Wondered: At Age's End
ags:dayofthefish               Day of the Fish
ags:ddddd                      DDDDD: The Draft Drifter Who Dashed Doctor Dunno
ags:ddr                        Dennis Dennis Revolution
ags:deaddimension              Dead Dimension
ags:deadgods                   Dead Gods: Haizara 2
ags:deadhand                   Dead Hand
ags:deadinspace                Dead in Space
ags:deadlyconsequences         Deadly Consequences!
ags:deadmanpoliticalparty      Dead Man's Political Party
ags:deadofwinter               Dead of Winter
ags:deadpixels                 Dead Pixels
ags:deadroom                   Dead Room
ags:deadsilence                Dead Silence
ags:deadstar                   Dead Star
ags:deathandtransfiguration    Death and Transfiguration
ags:deathasitis                Death as it Is
ags:deathep1                   Death - Episode One: The scythe of unlimited power
ags:deathofanangel             Death of an Angel
ags:deathofdavyjonesscenario   Yet Another Death of Davy Jones Scenario
ags:deathonstage               Death on Stage
ags:deathsdoor                 Death's Door
ags:deathsquest                Deat(h)'s Quest
ags:deathworeendlessfeathersdisk1 Death Wore Endless Feathers Disk 1
ags:deckhex                    DeckHex
ags:deephope                   Deep Hope
ags:deepspacemission           Deep Space Mission: Are we alone?
ags:deflus                     Deflus
ags:dehaunt                    Dehaunt
ags:deity                      Deity
ags:delerium                   Delerium
ags:dellamorte                 Dellamorte Dellamore
ags:demogame                   JWB Games Demo Game
ags:demonday                   Demon Day
ags:demonicdollhouse           The Demonic Dollhouse
ags:demonslayer5               Demon Slayer 5
ags:derrekquest                Derrek Quest I: Lost in the desert
ags:derverschwundenehusky      Der verschwundene Husky
ags:desertminer                Desert Miner
ags:desmond                    Desmond: The 'Thing' from another world!
ags:desolate                   Desolate
ags:detectivebhmini            Detective Boiled Hard Mini Case
ags:detectiveobriced           Detective O.Briced
ags:detectiverizal             Detective Rizal and the Jaded Ruby
ags:detention                  Detention!
ags:devilgotwoman              The Devil Got My Woman
ags:devochkaquest              Devochka Quest
ags:dexter                     Dexter Morning Routine
ags:dgsearchbatteries          Another DG game: the search of the batteries
ags:dicklarenzo                Dick LaRenzo: Secret Agent!
ags:diemaskennyarlathoteps     Die Masken Nyarlathoteps
ags:dimetrodon                 Day of the Dimetrodon
ags:dinnerforpigeons           Dinner for Pigeons
ags:dirandiouskroken           Dirandious Kroken
ags:disappearancetime          007 ¾: Disappearance Time
ags:disgust                    Disgust
ags:dislocation                Dislocation
ags:disquiet                   Disquiet
ags:distancenoobject           Distance no object
ags:doctormaze                 The Amazing Doctor Maze
ags:doctormuttonchop           Doctor Muttonchop
ags:doctorwho                  Doctor Who: Time Snare
ags:doctorzoo                  The Everyday Adventures of the Evil Dr. Zoo
ags:dogescape                  Dog Escape
ags:dollshouse                 dolls house
ags:dollshouseinsanity         dolls house: INSANITY
ags:dommep1                    Day of Maniac Mansion - Ep. 1: Les aventuriers des grottes perdues
ags:donalddowell               Donald Dowell and the Ghost of Barker Manor
ags:donkeybas                  Donkey.Bas AGS Remake
ags:donnaavengerofblood        Donna: Avenger of Blood
ags:donniedarko                Donnie Darko - The Adventure Game
ags:donspillacyconspiracyquest Don Spillacy's Conspiracy Quest
ags:dontdrinkthepink           Don't Drink the Pink
ags:donthedweebdancedilemma    Don the Dweeb: Dance Dilemma
ags:donticeyourcool            Don't Ice Your Cool
ags:dontlook                   Don't Look!
ags:dontpush                   Don't Push The Button
ags:dontworrybaby              Don't Worry Baby
ags:dontworryillbringthebeer   Don't Worry, I'll Bring The Beer!
ags:doomgraphicadventure       Doom: A Very Graphic Adventure
ags:doors                      Doors
ags:doses                      Doses
ags:dovadulasburn              DoVaDuLa'S BuRn
ags:draconis                   Draconis
ags:draculator2                Draculator II: Byte of the Draculator
ags:dragonorb                  Dragon Orb
ags:dragonscale                Dragonscale: The Encounter
ags:dragonsfang                Dragon's Fang
ags:dragontales                Dragon Tales
ags:drchuckles                 Dr. Chuckles' Miniature World Of Madness
ags:dreadmacfarlane            Dread Mac Farlane
ags:dreadmacfarlane2           Dread Mac Farlane - Part 2
ags:dreadmacfarlaneapprentie   Dread Mac Farlane, apprentie pirate
ags:dreamagine                 Dreamagine
ags:dreamer                    Little Dreamer
ags:dreamsofwintermass         Dreams of Winter Mass
ags:dreamychristmas            Create your own adventure game: Your dreamy Christmas
ags:dressedforafight           Dressed for a Fight Out
ags:drevil                     Dr. Evil
ags:drillkiller                DRILL KILLER
ags:drlutztimetravelmachine    Dr.Lutz Time Travel Machine
ags:drugsandalians             drugs and alians
ags:drunkfredcell              Drunk Fred in the Cell
ags:dumbassdrivers             Dumbass Drivers!
ags:dungeonhands               Dungeon Hands
ags:duskhunters                Dusk Hunters
ags:dusttowater                Dust to Water
ags:dutyandbeyond              Duty and Beyond
ags:dutyfirst                  Duty First
ags:duzzquest                  DuzzQuest: An Egotistic Adventure
ags:duzzquest2                 DuzzQuest2
ags:dysmaton                   Dysmaton
ags:earlbobby1                 Earl Bobby is looking for his Shoes
ags:earlbobby2                 Earl Bobby is looking for his Balls
ags:earlbobby3                 Earl Bobby is looking for a Loo
ags:earlmansinthebreakout      Earl Mansin: The Breakout
ags:earthlingpriorities        Earthling Priorities
ags:earthstory                 Earth Story
ags:easterencounter            Easter Encounter
ags:easterinron                Easter in Reality-on-the-Norm
ags:easterislanddefender       Easter Island Defender
ags:echidna                    Echidna Chwest
ags:echoesofterra              Echoes of Terra
ags:echoesofthepast            Echoes of the Past
ags:echointheclouds            Echo in the Clouds
ags:edmund                     Edmund and the potato
ags:eerieblue                  Eerie Blue
ags:egoplanetapes              Ego in Planet of the Apes
ags:egress                     Egress - The Test of STS-417
ags:eight                      8
ags:eikos1                     La Légende d'Eikos chapitre 1 : Le Seigneur des Loups
ags:eikos2                     La Légende d'Eikos chapitre 2 : Réveil dans la Nuit
ags:electrokit                 Maaikes Elektrokit
ags:elevator                   The Elevator
ags:elevatorriseabyss          The Elevator - Rise from the Abyss!
ags:elfer                      Elfer
ags:elfmotorsinc               Elf Motors Inc.
ags:elforescuecraby            ELFO: Rescue Craby
ags:elfthe4elements            ELF: The 4 elements
ags:elfthedarkness             ELF: And soon the darkness...
ags:eliminationbyimprovisation Elimination by Improvisation
ags:elmowagon                  Elmo's Wagon Conflict
ags:emeraldeyes                Emerald Eyes
ags:emilyenough                Emily Enough: Imprisoned
ags:emmaroide                  Emma Roide
ags:emptymindblankfate         Empty Mind - Blank Fate
ags:encounters                 Encounters of the Closest Kind
ags:endlessloop                Endless Loop
ags:enoworld                   Enoworld
ags:enqueteolonnes             Enquête au pays des Olonnes
ags:enterthestory              Enter The Story
ags:entrapment                 Entrapment
ags:entrapped                  Entrapped
ags:equilibrium                Equilibrium - Out of Time
ags:erictheanteater            Eric the Anteater
ags:erkrealestate              Erk: Adventures in Stone Age Real Estate
ags:errand                     Errand
ags:escape                     Escape
ags:escapefromasmallroom       Escape From a Small Room 1: The walls are closing in
ags:escapefromevergreenforest  Escape From Evergreen Forest
ags:escapefromlurrilous        Escape from Lurrilous
ags:escapefromterrorbay        Escape From Terror Bay
ags:escapefromthechaoticcity   Escape From The Chaotic City
ags:escapefromthegarage        ESCAPE from the garage
ags:escapefromthesalemmoons    Escape From The Salem Moons
ags:escapefromthezombiecity    Escape From The Zombie City
ags:escapeledgeoctagon         Escape The Ledge: Octagon
ags:escapethebarn              Escape the Barn
ags:escapetheship              Escape the ship
ags:escapetocivilization       Escape to Civilization
ags:esper                      ESPER: The Town on the Edge of Darkness
ags:essence                    Of the Essence
ags:essenceofimagination       Essence of Imagination
ags:essia                      Essia
ags:etaac                      Electronic Tax Administration Advisory Committee
ags:etaitungeek                Il était un Geek
ags:eternalchrysalis           Eternal Chrysalis
ags:eternallyus                Eternally Us
ags:eternaltorpor              Eternal Torpor / Sopor Eterno
ags:eventtimer                 Event Timer
ags:everlight                  Everlight Forest
ags:evil                       Evil
ags:evilenterprises            Evil Enterprises
ags:evillodge                  Evillodge: The Criminal Adventure Game
ags:exclamation                !
ags:exit                       EXIT
ags:exmachina                  Ex Machina
ags:explorationa               Exploration A
ags:exposedreality             Exposed Reality
ags:everythingm                Everything that Begins with an M
ags:fadingshades               Fading Shades
ags:fakethemoonlanding         Fake the moon landing
ags:fall                       Fall
ags:fallenangel                Fallen Angel
ags:fallenhero                 Fallen Hero
ags:fallensoldier              Fallen soldier
ags:fallingdark                Falling Dark
ags:fallingdark2               Falling Dark 2: Relapse
ags:familieherfurth            Der neue Wahnsinn der Familie Herfurth
ags:fanbots                    Fanbots
ags:fantasymotus               Fantasy Motus
ags:farcorners1                The Far Corners of the World: Chapter 1 - The Book, the Box and the Key
ags:farnowhere                 FAR NOWHERE
ags:fashiongirl                Fashion Girl
ags:fasmo                      Fasmo!
ags:fasmogoeswest              Fasmo 2: Fasmo Goes West
ags:fayeking                   Faye King: Jungle Jeopardy
ags:fbiquest                   FBI Quest
ags:fearaphobia                Fearaphobia
ags:featherweight              Featherweight
ags:femspray                   FemSpray
ags:fengshuitv                 Feng Shui And The Art Of TV Reception
ags:ferragosto                 Elia, Ilaria & the Kids Having a Good Time at the Sea (or at least they try)
ags:feuersturm1                Feuersturm - Kapitel 1: Zurück in die welt
ags:feuersturm2                Feuersturm - Kapitel 2: Der unheimliche Zug
ags:feuersturm3                Feuersturm - Kapitel 3: Wo Der Wald Beginnt...
ags:fhaloness                  Fhaloness
ags:fifa2004                   FIFA International Football 2004
ags:fightforlife               Fight for Life
ags:finger                     Finger of suspicion
ags:fireflystory3d             Firefly story 3D
ags:firstdrop                  1st Drop
ags:firststitch                The Tapestry - Prologue: The First Stitch
ags:fistsofmurder              Fists of Murder
ags:fixer                      Fixer
ags:fixumdude                  Fixumdude's 3D Printing Adventure
ags:flamebarrels               Flame Barrels
ags:flashbax                   Flashbax
ags:flashmccoy                 Flash McCoy
ags:flightrobots               Flight from the Robots
ags:flightrobotsch2            Flight from the Robots - Chapter 2
ags:floatyrog                  Floaty Rog'
ags:flophouse                  Flophouse Hijinks
ags:flowergirl                 Flower Girl
ags:flukie                     Flukie
ags:fluxworld                  Flux World
ags:flyingthinker              Flying Thinker
ags:flypaper                   Fly Paper
ags:focality                   Focality
ags:foggydawn                  Foggy Dawn
ags:foggynotions               Foggy Notions
ags:foodwars                   Food Wars
ags:foolaround                 Fool Around
ags:forcemajeureiithezone      Force majeure II: The Zone
ags:forest                     Forest
ags:forestdweller              Forest Dweller 3D
ags:forfrogssake               FOR FROGS SAKE! GET THE FROG OUT!
ags:forge                      Forge: Chapter One
ags:forgerecap                 Forge: Loom Recap
ags:forgettendeath             Forgetten Death
ags:forms                      Forms
ags:fortressofwonders          Fortress of Wonders
ags:foundations                Foundations
ags:fountainofyouth            Indiana Jones and the Fountain of Youth
ags:framed                     Framed!
ags:frameonthewall             The Frame on the Wall
ags:frankenpooper              Frankenpooper
ags:frankfurter1               The Adventures of Stanley 'Frankfurter' Jones
ags:frankfurter2ch1            Frank Further: The Further Adventures of Stanley 'Frankfurter' Jones - Chapter I
ags:frankstallone              Frank Stallone: The Driver and Mob Enforcer
ags:frankthefarmhandpart1      Frank the Farmhand - Part 1: The Big Escape
ags:frankthefarmhandpart2      Frank the Farmhand - Part 2: The Secret of Guija
ags:franticfranko              Frantic Franko: A Bergzwerg Gone Berserk
ags:frasiercraneseattlerampage Frasier Crane: Seattle Rampage
ags:freakchic                  Freak Chic
ags:fredandbarneymeetthefuture Fred and Barney meet the future
ags:fribbeldib                 Fribbeldib
ags:fridgefollies              Fridge Follies
ags:frightfest                 FrightFest: Dracula vs. Frankenstein vs. The Mummy
ags:fritz                      Fritz
ags:frogisland                 Frog Island
ags:frozenkingdom              Frozen Kingdom
ags:fsis1000000quest           FSi's $1000000 Quest!
ags:fsisachequest              FSi's Ache Quest
ags:fsisalienation             FSi's Alienation!
ags:fsiscotmattcehotsvd        FSi's CotMATtCEHotSVD
ags:fsismhcfhr                 FSi's MHCFHR!
ags:fsispowercowfromuranus     FSi's PowerCow From Uranus!
ags:fuguestate                 The Man From Fugue State
ags:fulkramick                 Fulkramick's Dreamting: An Interactive Adventure
ags:furballs1                  Fur Balls 1 - evil be thy name: Bundles of mayhem!
ags:funnyboneyard              The Funny Boneyard
ags:funsunmishaps              Fun, Sun & Mishaps
ags:funwithnumbers             Fun With Numbers
ags:futuramatrivia             Futurama: Who Said That?
ags:futurecity3000             Future City 3000
ags:gabyking                   The Young Gabriel King Chronicles
ags:galaxyquest                Galaxy Quest: The Arkainian Artifact - Part I
ags:gamequest                  Game Quest
ags:gamesgalore                Games Galore!
ags:garbheileach               The Secret of Garbh Eileach
ags:garfieldlasagna            Garfield: Attack of the Mutant Lasagna
ags:gassesuittollis3           Gasse Suit Tollis 3: Looking for Love
ags:gatewayremake              Gateway Remake
ags:gaygreg                    Gay Greg is Grounded
ags:gemcollector               Gem Collector
ags:genbu                      Genbu's Favour
ags:geometricshapes1circleboy  Geometric Shapes 1: Circleboy
ags:gesundheit                 Gesundheit!
ags:getawayfrompluto           Get away from PLUTO
ags:getfood                    Get food
ags:getsquirty                 Get Squirty!
ags:gettingpicture             Getting the Picture
ags:ghostcatchers              GhostCatchers
ags:ghostvirus                 Ghost Virus Invasion
ags:ghostvoyage                Ghost Voyage
ags:giftingspirit              Gifting Spirit
ags:girlandrabbit              Educating Adventures of Girl and Rabbit
ags:gladiatorquest             Gladiator Quest
ags:glitchquest                Glitch Quest
ags:globalistagenda            My Dear Globalist Agenda
ags:gnomeshomebrewingadventure Gnome's Homebrewing Adventure
ags:gnrblex                    GNRBLEX
ags:goatburn                   Goat Burn
ags:goatherd                   Goat Herd and the Gods
ags:goldreddragon              Gold of the Red Dragon
ags:goneboatfishin             Gone Boat Fishin'
ags:gonefishin                 Gone fishin'
ags:gonemyangel                Gone, My Angel, Gone
ags:gonorth                    Go North
ags:gonorth2                   Go North 2
ags:goodgod                    Good God!
ags:goodmorningmrgingerbread   Good Morning, Mr. Gingerbread!
ags:goodsantabadsanta          Good Santa, Bad Santa
ags:goontang                   Goontang Chackalaka
ags:gotalight                  Got a Light?
ags:gpslostadventure           G.P.'s Lost Adventure
ags:grandkitchenescape         Grand Kitchen Escape
ags:granville1                 The Granville Chronicles - Part 1: The Rebellion Begins
ags:graveyard                  Graveyard
ags:gravitytestgame            Gravity's Test Game
ags:gray                       Gray
ags:greenback                  Greenback - Prologue
ags:grizzlygooseofgosse        Grizzly Goose of Gosse
ags:groundhog                  Groundhog
ags:grr                        Grr! Bearly Sane
ags:guardiansofgold            Guardians of Gold
ags:guyhookcrook               Guy: by hook or by crook
ags:guyredplanet               Guy who landed on weird red planet
ags:guyslug                    Guy Slug: Private Eye
ags:guyver1d                   Guyver 1D
ags:guyverquest1               Guyver Quest I: Sho Adventure
ags:guyverquest2               Guyver Quest II: Cronos
ags:gwendarkly                 Gwen Darkly: A Speechless Case
ags:hack                       Hack
ags:hackenslashisland          The Mystery of Hackenslash Island
ags:halloween                  Halloween
ags:halloweenguest             Halloween with an unexpected Guest
ags:halloweenhorror            Halloween Horror
ags:halloweenparty             The Halloween Party
ags:hallwayofadventures        Hallway of Adventures
ags:hamresanden2               The Hamresanden Chronicles II: The Black Prism
ags:hamster                    No one touches my Hamster
ags:hangon                     Hang On
ags:happyduckieadventure       Happy Duckie Adventure
ags:happyface                  ^_^
ags:hardspace                  Hard Space: Conquest of the Gayliks!
ags:harrycaine                 Harry Caine UNRATED
ags:harrypotterrpg             Harry Potter RPG
ags:harrys21stbirthday         Harry's 21st Birthday
ags:harryshopshock             Harry and the Locked Crocs Shop Shock
ags:hauntedcastle              Haunted Castle
ags:haven1                     Haven - Episode 1
ags:hawkeye                    Hawk Eye Quandaries
ags:headbangerheaven           Headbanger's Heaven - A Rock & Roll Adventure
ags:headoverheels              Head over Heels
ags:heartofabraxas             Heart of Abraxas
ags:heartland                  Heartland
ags:heatwave                   Heatwave
ags:heavenhell                 Heaven, Hell and the Neitherworld
ags:heavymetalnannulf          Heavy Metal Nannulf: The Strange Stage
ags:hecamethroughthedoor       He Came Through the Door
ags:heed                       Heed
ags:helloneighbor              Hello Neighbor!
ags:hellotaxi                  Hello! Taxi!
ags:hellspuppy                 Hell's Puppy
ags:helpthegame                HELP! the game
ags:helycia                    Hélycia
ags:hendrixisland              HENdRIX' Island
ags:henkstroemlostincellar     Henk Stroem in: Lost In Cellar
ags:henman                     Hen Man: Origins
ags:henrysmith                 Henry Smith and the Looters of Peru
ags:herby                      Herby
ags:herenosirens               Here Be NO Sirens
ags:heroeswyrdale              Heroes of Wyrdale
ags:heroinesquest              Heroine's Quest: The Herald of Ragnarok
ags:heroquestbeuk              HeroQuestBeuk
ags:hesgonehistorical          He's Gone Historical
ags:hewatches                  He Watches
ags:hhgtgtowelday              H2G2: Towel Day
ags:hiddenplains               Hidden Plains
ags:hiddentreasureryansfortune Hidden Treasure: Ryan's Fortune
ags:hide                       Hide
ags:him                        Him
ags:hitchhikersguidetothegalaxyremake The Hitchhiker's Guide to the Galaxy Remake
ags:hitthefreak                Hit the Freak
ags:hiyah                      HiYah!
ags:hjarta                     Hjarta
ags:hlobb                      The Historical League of Bouncy Boxing
ags:hoik                       Hero of Infamous Kingdoms
ags:homesweetron               Home Sweet Reality-on-the-Norm
ags:honksadventure             Honk's Adventure
ags:hood                       Hood
ags:hookhook                   Hook's hook!
ags:hope                       Hope
ags:hoppinghomeward            Hopping Homeward
ags:horseparkdeluxe            Horse Park DeLuxe
ags:horseparkfantasy           Horse Park Fantasy
ags:hotelhansen                Hotel Hansen
ags:hotelhijinks               Hotel Hijinks
ags:housedesade                House of de Sade
ags:houseofhorror              House of Horror
ags:housequest2                House Quest 2
ags:howmany                    How many...
ags:howtheyfoundsilence        How They Found Silence
ags:hpunk                      H_PUNK_//
ags:hubris                     Hubris - A Popular Pub Pastime
ags:hugglestrip                Huggles Goes On A Trip!
ags:hungry                     Hungry
ags:hungryworm                 Hungry Worm
ags:huongjiaoping              Huong Jiao Ping
ags:huxzadventure              Huxz Adventure
ags:hybrid                     Hybrid
ags:hydeandseek                Hyde and Seek
ags:hydrate                    HYDRATE
ags:hypnotoad                  Hypnotoad
ags:iamjason                   IAMJASON
ags:icantsleep                 I Can't Sleep in Silence - It's Always Darkest
ags:icecreammystery            The Ice Cream Mystery
ags:iceintheair                Ice in the Air
ags:icestationzero             Ice Station Zero
ags:id                         iD
ags:iforgot                    I Forgot...
ags:iggrok                     Instagame: Grok
ags:igspaceadventure           Instagame: Space Adventure
ags:igspaceadventurer          Instagame: Space Adventurer
ags:igspaceoddities            Instagame: Space Oddities - Zoip's Escape!
ags:igstrangeplanet            Instagame: The Strange Planet
ags:iiispy                     III-Spy
ags:iisstabbings               From Hell's Hart, I is Stabbings: An Oceanspirit Dennis Tale
ags:illuminationdiminishing    Illumination Diminishing
ags:illuminum                  ill-uminum
ags:illusion                   Illusion
ags:imfree                     I'm free / Soy libre
ags:imnotcrazyrightthecell     I'm not crazy, right? - The Cell
ags:imnotcrazyrightthewell     I'm not crazy, right? - The Well
ags:imonlysleeping             I'm Only Sleeping
ags:impostersyndrome           Imposter Syndrome
ags:imstillhere                I'm still Here
ags:inbloom                    In Bloom
ags:inconvenience              inconvenience
ags:indyatp                    Indiana Jones: ATP-fr Test
ags:indyaventuriers            Indiana Jones et les aventuriers de l'arche perdue
ags:indyberceau                Indiana Jones et le Berceau de l'Hiver
ags:indybones                  Indy Bones: The Book of the Gods
ags:indycomingofage            Indiana Jones - Coming of Age
ags:indycrownofsolomon         Indiana Jones and the Crown of Solomon
ags:indycrystalcursor          Indiana Jones and the Window of the Crystal Cursor
ags:indygoldofgenghiskhan      Indiana Jones and the Gold of Genghis Khan
ags:indynouvelan               Indiana Jones et les aventuriers du nouvel an
ags:indypassageofsaints        Indiana Jones and the Passage of Saints
ags:indyrelicoftheviking       Indiana Jones and the relic of the Viking
ags:indyroyaume                Indiana Jones et le Royaume des Voeux
ags:indysevencities            Indiana Jones and the Seven Cities of Gold
ags:indianarodent              Indiana Rodent: Raiders of the Lost Cheese
ags:infantrydivision           Infantry Division 1338
ags:infectionep1               Infection - Episode I: The Ship
ags:infectionep2               Infection - Episode II: The Station
ags:inferno                    Inferno: the demo of a rotten bastard
ags:infinitemonkeys            Infinite Monkeys
ags:infinitybit                Infinity Bit
ags:inlimbo                    In Limbo
ags:innersanctum               Inner Sanctum
ags:insanebert                 Insane Bert
ags:insidemonkeyisland         Inside Monkey Island
ags:insidemonkeyislandch2      Inside Monkey Island: 2nd chapter
ags:insidemonkeyislandch3      Inside Monkey Island: 3rd chapter
ags:insidemonkeyislandch4      Inside Monkey Island: 4th chapter
ags:inspectorgismoe            Inspector Gismoe
ags:integerbattleship          Integer Battleship
ags:intergalacticspacepancake  Intergalactic Space Pancake!
ags:interstellarborders        Interstellar Borders
ags:intestinator               Intestinator!
ags:intothelight               Into The Light
ags:intraworld                 Intra-World
ags:intraworld2                Intra-World 2
ags:inversion                  Inversion
ags:invincibleisland           Invincible Island Remake
ags:ioawn4t                    If On A Winter's Night, Four Travelers
ags:irentedaboat               I Rented a Boat
ags:irishcoffee                Irish Coffee
ags:isaacodyssey               Isaac's Odyssey
ags:isnkill                    ISN: Kill!
ags:isos                       I.S.O.S.
ags:ispy2                      I Spy II
ags:itsabugslife               It's a Bugs Life
ags:itsjustarongame            It's Just a Reality-on-the-Norm Game
ags:iwalkedapath               I Walked a Path
ags:iwantanidentity            I want an Identity / Quiero una Identidad
ags:iwantout                   I Want Out!
ags:iwanttodie                 I want to die / Quiero Morir
ags:iwanttodieremake           I want to die / Quiero Morir Remake
ags:iwwhiiwwhitomirotpgthegame IWWHIIWWHITOMIROTPG: The Game!
ags:jack                       JACK
ags:jacktrasheaterch1          Jack Trasheater - Chapter I: Pain House! / Jack Trasheater e la Casa del Dolore
ags:jacktrekker                Jack Trekker - Somewhere in Egypt
ags:jacob                      Jacob
ags:jacobvacut                 Jacob - VertigoAddict's cut
ags:jacquelinewhitecurseofthemummies Jacqueline White - Curse of the Mummies
ags:jacquelinewhitereddesert   Jacqueline White - Bad Trouble in the Red Desert
ags:jailhouse                  Jail House Breakdown
ags:jakelastjourney            Jake's Very Last Journey
ags:jamesbond                  James Bond
ags:jamesinneverland           James in Neverland
ags:jamesperis                 James Peris es el agente 00,5
ags:jamesperis2                James Peris 2
ags:jasongoldenapple           Jason and the Golden Apple
ags:javelincatch               Javelin Catch
ags:jetpacksam                 Jetpack Sam
ags:jimmsquest3                Jimm's Quest III: Lesko's Revenge
ags:jimmysday                  Jimmy's Day
ags:jimmythetroublemaker       Jimmy The Troublemaker
ags:joeshorriblehell           Joe's Horrible Hell
ags:joesmiserablelife          Joe's Miserable Life
ags:johnharris                 John Harris and the Treasure of the Pharaoh
ags:johnjebediahgun            John Jebediah Gun and Sepheret Island
ags:johnlosthiskeyep1          John Lost His Key - Episode 1
ags:johnlosthiskeyep2          John Lost His Key - Episode 2
ags:johnnyrocket               Johnny Rockett Adventure
ags:johnsinclair               John Sinclair - Voodoo in London
ags:jonahsplace                Jonah's Place
ags:jonnyfeces                 Jonny and the sweet fragrance of feces
ags:jonstickman                Jon Stickman
ags:journey                    Journey
ags:journeyhome                Journey Home
ags:journeyhell                Journey to Hell
ags:jugglequest                Roger's Juggle Quest
ags:juliusdangerous1           Julius Dangerous .. and the space invaders
ags:juliusdangerous2           Julius Dangerous 2
ags:jumpinjack                 Jumpin' Jack: the bean powered kid
ags:jumpinjones                Jumpin' Jones in: The Big Switch-Off
ags:jumpjackflash              Jump! Jack! Flash!
ags:june20th                   June 20th
ags:justanotherpointnclickadventure Just Another Point n Click Adventure
ags:justyouandme               Just You And Me
ags:kada                       Ka and Da
ags:kanjigakusei               Kanji Gakusei
ags:karelianninja              Karelian Ninja
ags:kartquest                  Kart-Quest
ags:kata                       KATA
ags:katurachroniques           Les Chroniques de Katura
ags:katurachroniquesrpg        Le Jeu de Rôles des Chroniques de Katura
ags:katuracolonisation         Katura Colonisation
ags:katuralchimie              KaturAlchimie
ags:katurapuzzleadv            Katura Puzzle Adventure
ags:katurapuzzlearenas         Katura Puzzle Arenas
ags:katurarpg                  Katura RPG
ags:keptosh1                   Keptosh I: The Search for junc
ags:keyboardmadness            Keyboard Madness
ags:keysofagamespace           Keys of a gamespace. An expressive game
ags:killereye                  Killer Floating Eye
ags:killjoseda                 Kill Joseda
ags:killmenow                  Kill Me Now
ags:kingdomlegend1             Kingdom Legend
ags:kingdomlegend2             Kingdom Legend 2
ags:kingofrock                 The King of Rock in: Riding the Wild Wind
ags:kingrobert                 King Robert's Quest: The Frustratingly Early Access Adventure
ags:kingsleyroad               Kingsley Road, 1980
ags:kingsquestfororgy          King's Quest for Orgy
ags:kinkyisland                Kinky Island
ags:kirja                      Kirjastotäti
ags:kittenadv                  Kitten Adventures
ags:kittyquest                 Kitty Quest
ags:knightquestforgoldenring   Knight Quest for the Golden Ring
ags:knightsquest3              Knight's Quest III - Tides of Merania
ags:knightsquest4              Knight's Quest IV - Here Today, Gone to Yesterday
ags:knightsquire               KnightSquire
ags:knobblycrook               The Knobbly Crook
ags:knobblycrookch1            The Knobbly Crook - Chapter 1: The Horse You Sailed In On
ags:knorrig                    Knorrig the Gifted Troublemaker
ags:koddurova                  Kod Durova
ags:koffeekrisis               Koffee Krisis
ags:kongbaghdad                Kong Over Baghdad
ags:korinsmines                Korin's Mines
ags:koscheitheimmortal         Koschei The Immortal - The Beginning
ags:kq3plus                    King's Quest III+
ags:kq4retold                  King's Quest IV: The Perils of Rosella Retold
ags:kq9vga                     King's Quest IX: The Silver Lining VGA
ags:kristmaskrisis             Kristmas Krisis
ags:ktx1                       KTX-1
ags:kumastory                  Kuma Story
ags:laboite                    La boite
ags:labratescape               Lab Rat Escape
ags:labratmaze                 Lab Rat Maze!
ags:labyrinth                  Labyrinth
ags:lacarbonara                La Carbonara
ags:lacicuta                   La Cicuta
ags:lacroixpan                 La Croix Pan
ags:lagrancastanya             La Gran Castanya
ags:lagrandeplaine             La Grande Plaine
ags:lallaveyfabianshones       La Llave y Fabian Shones
ags:lamaleta                   La Maleta
ags:lancethepenguin            Lance The Penguin
ags:laodiseadelfracaso2        La Odisea del Fracaso II
ags:laportenoire               AAaaah!! La porte noire
ags:lasol                      Submerged - LaSol
ags:lastclown                  Last Clown Standing
ags:lasthope                   Last Hope
ags:lastlightpost              The Last Light Post
ags:lastnfurious               Last'n'Furious
ags:latelastnite               Late Last Nite
ags:laundryday                 Laundry Day
ags:lavablava                  Lava Blava
ags:lazaruswantspants          Lazarus Wants Pants
ags:lazytownthenewkid          LazyTown: The New Kid
ags:lechuckstories             LeChuck Stories
ags:legacyicecream             The Legacy of Icecream Man
ags:legendofrovendale          Legend of Rovendale
ags:legendofseththebard        The Legend of Seth the Bard
ags:legendofskystones          Legend Of Sky Stones
ags:legendsofmardaram          Legends of Mardaram
ags:leisuresuitlarry2          Leisure Suit Larry 2 - Point and Click Remake
ags:leisuresuitlarrylil        Leisure Suit Larry: Lost in Love!
ags:lelac                      Le Lac
ags:lemasabachthani            Lema Sabachthani
ags:leopoldkettle              The Surprisingly Short Adventure of Leopold Kettle
ags:lesmiserables              Les Miserables
ags:lessthanthree              <3 (Less Than Three)
ags:letscook                   Let's Cook - School of Cooking with Koala
ags:letteraamorosa             Lettera Amorosa
ags:libremotus                 Libre Motus
ags:lichdom                    Lichdom - "Where did I put that..."
ags:life                       Life
ags:lifeboatstoryofcedrick     Lifeboat: The Story of Cedrick
ags:lifeinabox                 Life in a Box
ags:lifeofdduck                Life of D. Duck
ags:lifeofdduck2               Life of D. Duck II
ags:liftreasureofthetanones    Lif and the Treasure of the Tanones
ags:lightcycles                AGS Cycles
ags:lightningmaster            Lightning Master
ags:likeadream                 Like A Dream
ags:likeafox                   Like a Fox!
ags:lillywizard                Lilly the Wonder Wizard
ags:limeylizardwastewizard     Limey Lizard: Waste Wizard!
ags:linegame                   Line Game
ags:linkattus                  The Devious and Daring Commando Raid of Linkattus
ags:linnprotector              Linn the Protector and the Seven Daughters of Ran
ags:lionsden                   The Lion's Den
ags:littlegirlinunderland      Little Girl in Underland
ags:littleleonardo             Little Leonardo
ags:littlesimulatedpeople      Little Simulated People
ags:livingnightmare            Living Nightmare
ags:livingnightmareendlessdream Living Nightmare: Endless Dreams
ags:livingnightmarefreedom     Living Nightmare: Freedom
ags:loathesome                 The Loathesome Man
ags:lockedin                   Locked In
ags:lockedout                  Locked Out
ags:lockeescape                Locke's Escape
ags:loftusandtheskycap         Loftus and the Sky Cap
ags:lonecase1                  Lone Case: Locomotive Breath
ags:lonecase2                  Lone Case 2: Scars
ags:lonecase3                  Lone Case 3: Showdown
ags:lonecase4                  Lone Case 4: Epitaph
ags:lonelynight                Lonely Night
ags:longestwinter              The Longest Winter
ags:longexpectedfriday         Long expected Friday
ags:lonkeyisland               The Tale of Lonkey Island
ags:lookingfordread            Looking For Dread Mac Farlane / A la recherche de Dread Mac Farlane
ags:loomiireturnoftheswans     Loom II: Return of the Swans
ags:loonyisland                The Mystery of Loony Island
ags:lordoflight                Lord of Light
ags:losjovenesdelaguerra       Los Jovenes De La Guerra
ags:lostanswers                Lost Answers
ags:lostdollar                 Max Griff in: The Lost Dollar
ags:lostinparadise             Lost In Paradise
ags:lostinthenightmare         Lost In The Nightmare
ags:lostinthenightmare2        Lost In The Nightmare 2: Unforgettable Memories
ags:lostinthewoods             Lost In The Woods
ags:lotto                      Lottó
ags:lucasmaniac                Lucas Maniac!
ags:lucasmendoza               Lucas Mendoza, Amateur Detective: The Searchers of The Beginning
ags:lucidlucy                  LUCID LUCY
ags:lucylavender               The Amazing Adventures of Lucy Lavender
ags:lukesexistentialnightmare  Luke's Existential Nightmare
ags:lunarlander                Lunar Lander
ags:lutherinhood               Luther in the Hood
ags:lydia                      Lydia
ags:lydianellreno              Lydia and the Mystery of Nellreno Manor
ags:lygophilous                Lygophilous
ags:machinesdreams             Machines Have Lucid Dreams
ags:maelstrom                  Maelstrom Obscura - Case 1: The Legend of the Loch Ness Monster
ags:mafaldawest                Mafalda: The Strange and Unusual life of Mafalda West, Part 1
ags:magic8ball                 Magic-8-Ball
ags:magicalwhatevergirl        Magical Whatever Girl Rocks Out In The Stone Age
ags:magicballoffortune         Magic Ball of Fortune
ags:magicowl                   Magic Owl
ags:magnumpm                   Magnum, P.M
ags:magsic                     Magsic
ags:magsic2                    Magsic II
ags:majorbummerdude            Major Bummer Dude: Lassi Quest Reality-on-the-Norm
ags:mammamia                   Mamma Mia! Winter Ice Cream Mayhem
ags:manamatch                  Mana Match
ags:manboy                     Man Boy vs. Doctor Sock
ags:mangivingup                Man Giving Up
ags:maniacapartment            Maniac Apartment
ags:maniacland                 Alice in Maniacland
ags:maniacmansiondeluxe        Maniac Mansion Deluxe
ags:maniacmansionds            Maniac Mansion DS
ags:maniacmansiondott          Maniac Mansion - DOTT-style Remake
ags:maniacmetalheadmania       Maniac Metalhead Mania
ags:maniacmetalheadmania2      Maniac Metalhead Mania II: The Heavy Metal Rescue Mission
ags:manvsfish                  Man vs. Fish
ags:mardsrevenge               Mard's Personal Little Revenge
ags:martyausdemall             Marty aus dem All
ags:martyroftime               A Martyr Of Time
ags:mash                       M*A*S*H*: The Point n' Click Adventure
ags:masked                     Masked
ags:masquerade                 Masquerade at the Con
ags:mastersofsound             Masters of Sound
ags:matildacurse               Matilda and the Curse of King Stephen
ags:matttothefuture            Matt to the Future
ags:maverickgunn               Maverick Gunn and the Eye of Oggun
ags:maxandmaggie               The Chronicles of Max and Maggie
ags:maxfury                    Max Fury
ags:maxparade                  Max's Parade
ags:mechanismo                 Mechanismo
ags:medicaltheoriesofdrkur     The Medical Theories of Dr. Kur
ags:megacorp                   Megacorp Redux
ags:megocannibaljungle         Me Go Cannibal Jungle!
ags:megostore                  Me Go Store!
ags:megostore2                 Me Go Store II: Me Go Away!
ags:megostore3                 Me Go 2008!
ags:melrin1                    Melrin: The Disciple Ordeal
ags:melrin2                    Melrin: The Pendant Quest
ags:melrin3                    Melrin: The Dragon Menace
ags:memoriae                   Memoriae
ags:memoriesfade               Memories Fade
ags:memoriesofasnake           Memories of a Snake / Memoires d'un Serpent
ags:memory                     This Game Might Improve Your Memory
ags:meninhats                  Men In Hats: Attack of the Evangelists
ags:merrychristmas             Merry Christmas, Alfred Robbins
ags:meshumba                   Meshumba's Reckoning
ags:messedupmothergoose        Messed-Up Mother Goose - DELUXE MY ASS: ENHANCED
ags:messgoblins                Mess Goblins
ags:meta                       META
ags:metaphobia                 Metaphobia
ags:meteorhead1                Meteorhead: Recycled
ags:meteorhead2                Meteorhead II: Rückkehr eines Idioten
ags:meteorhead3                Meteorhead III: Spiel mir das 1337 vom Tod
ags:meteorhead4                Meteorhead IV: Forgotten Memories
ags:meteorhead5                Meteorhead V: Die Universalkraft
ags:meteorhead6                Meteorhead VI: Verbannt ins Exühl
ags:meteorhead7                Meteorhead VII: Meteorhead Man und Peter Pommes retten die Fast Food-Industrie
ags:meteorhead8                Meteorhead VIII: Rettet Meteorhead Man
ags:meteorhead9                Meteorhead IX: Razors Mutation
ags:meteorhead10               Meteorhead X: Eine Frage der Ausrede
ags:meteorhead11               Meteorhead XI: Die Klauung des güldenen Headgars
ags:meteorhead13               Meteorhead XIII: Universale Veränderungen
ags:meteorhead14               Meteorhead XIV: A Road Movie
ags:meteorheadns3              Meteorhead - The New Series - Episode III: Die unverträgliche Dreistigkeit des Schweins
ags:meteorheadns4              Meteorhead - The New Series - Episode IV: Die Qual des Wals
ags:meteortale                 Meteor: A Tale About Earth's End
ags:mi                         Mi
ags:mi0daementia               Monkey Island 0 - Daementia
ags:mi0navidad                 Monkey Island 0 - Navidad
ags:mi12                       Monkey Island 1/2
ags:mi25escape                 Monkey Island 2.5 - Escape From Big Whoop
ags:mi25parque                 Monkey Island 2.5 - El parque de las Pesadillas
ags:mi5thereturnoflechuck      Monkey Island 5: The Return of LeChuck
ags:mibaddaytobedead           Monkey Island: Bad Day to be Dead
ags:micarnivalofthedamned      Monkey Island: Carnival of the Damned
ags:mickeymauserpart1          Mickey Mauser - Part 1: The Wrath of the Rat
ags:micv                       Monkey Island - Carnaval Vudú - Parte 1: La Busqueda
ags:midasheist                 The Midas Heist
ags:midnightsquadron           Midnight Squadron
ags:miguybrushson              Monkey Island - Guybrush's Son
ags:miillusion                 Monkey Island Illusion
ags:mikasdream2                Mika's Surreal Dream II: The Dream Comes True!?
ags:mikelechey                 Mike Lechey and the Forgotten Race
ags:mikesroom                  Mike's Room
ags:milkshake                  Milkshake
ags:mimv                       Monkey Island: La Maldicion Vudu
ags:mindboggler                MINDBOGGLER
ags:mindrape                   Mind Rape: Duress
ags:mindseye                   Mind's Eye
ags:minewadv                   Monkey Island - The new adventure
ags:minifeg                    Minifeg: The Search
ags:minorminion                Minor Minion
ags:miprision                  The Secret of Monkey Island - Prision Demo
ags:mirevealed                 The Secret of Monkey Island Revealed
ags:misc                       Misc
ags:missinginaction            Missing In Action
ags:missingsincemidnight       Missing since Midnight
ags:missionfutura              Mission Futura: The Mindless Menace / Mission Zukunftia
ags:missionfutura2             Mission Futura II: Der Zorn des Klon / Mission Zukunftia II
ags:mistdelaescueladearte      El Misterio de la Escuela de Arte
ags:misterybigwhoop            The Mistery of Big Whoop
ags:mistook                    The Man Who Mistook His Wife For a Hat
ags:mivl                       Monkey Island: Largo's Revenge / La Venganza de Largo
ags:mivoodoo                   The Voodoo of Monkey Island
ags:mmm1                       Maniac Mansion Mania Ep. 001: Sibling Love / Geschwisterliebe
ags:mmm2                       Maniac Mansion Mania Ep. 002: Commotion / Unruhen
ags:mmm3                       Maniac Mansion Mania Ep. 003: Stubenarrest
ags:mmm4                       Maniac Mansion Mania Ep. 004: Mimikry der Emotionen
ags:mmm5                       Maniac Mansion Mania Ep. 005: Rhythmen zum Reinbeißen
ags:mmm6                       Maniac Mansion Mania Ep. 006: Er is' weg
ags:mmm7                       Maniac Mansion Mania Ep. 007: Right said Fred!?!
ags:mmm8                       Maniac Mansion Mania Ep. 008: The Rebuff / Die Abfuhr
ags:mmm9                       Maniac Mansion Mania Ep. 009: Radioactive / Radioaktiv
ags:mmm10                      Maniac Mansion Mania Ep. 010: Tales of the Weird Ed
ags:mmm11                      Maniac Mansion Mania Ep. 011: Ein haariger Ausflug
ags:mmm12                      Maniac Mansion Mania Ep. 012: Serien-Special: GIGA Mansion
ags:mmm13                      Maniac Mansion Mania Ep. 013: Nur geträumt
ags:mmm14                      Maniac Mansion Mania Ep. 014: Ed's Rache für den Hamsterbraten
ags:mmm15                      Maniac Mansion Mania Ep. 015: Place Machine / Ortmaschine
ags:mmm16                      Maniac Mansion Mania Ep. 016: Meteor Family - The Return of the Meteor
ags:mmm17                      Maniac Mansion Mania Ep. 017: Das Labor
ags:mmm18                      Maniac Mansion Mania Ep. 018: Shit Happens!
ags:mmm21                      Maniac Mansion Mania Ep. 021: Rettet Kanal 13!
ags:mmm22                      Maniac Mansion Mania Ep. 022: Presserummel
ags:mmm23                      Maniac Mansion Mania Ep. 023: Das verflixte Geschenk
ags:mmm24                      Maniac Mansion Mania Ep. 024: Time Machine
ags:mmm26                      Maniac Mansion Mania Ep. 026: Zeitenwende
ags:mmm27                      Maniac Mansion Mania Ep. 027: Hamsternator
ags:mmm28                      Maniac Mansion Mania Ep. 028: Time Machine 2
ags:mmm29                      Maniac Mansion Mania Ep. 029: Flucht des Meteoriten
ags:mmm30                      Maniac Mansion Mania Ep. 030: Memories of Zak
ags:mmm31                      Maniac Mansion Mania Ep. 031: Britney's Quest / Britneys Suche
ags:mmm32                      Maniac Mansion Mania Ep. 032: The Secret of Maniac Mansion
ags:mmm33                      Maniac Mansion Mania Ep. 033: Carry on Smiley!
ags:mmm34                      Maniac Mansion Mania Ep. 034: Helden des Tages
ags:mmm35                      Maniac Mansion Mania Ep. 035: Weggebeamt
ags:mmm36                      Maniac Mansion Mania Ep. 036: Der Liebesbrief
ags:mmm37                      Maniac Mansion Mania Ep. 037: Date with Dave / Verabredung mit Dave
ags:mmm38                      Maniac Mansion Mania Ep. 038: Rescue Mission
ags:mmm39                      Maniac Mansion Mania Ep. 039: Erinnerungen
ags:mmm40                      Maniac Mansion Mania Ep. 040: Trapped in the cellar / Verflixte Türen
ags:mmm41                      Maniac Mansion Mania Ep. 041: The new Youth Protection Law / Das neue Jugendschutzgesetz
ags:mmm42                      Maniac Mansion Mania Ep. 042: Die furchtbaren Pläne des Psycho Bernie
ags:mmm43                      Maniac Mansion Mania Ep. 043: Vorsicht, Edna kommt!
ags:mmm44                      Maniac Mansion Mania Ep. 044: Razors grosser Auftritt
ags:mmm45                      Maniac Mansion Mania Ep. 045: Maniac Monday
ags:mmm46                      Maniac Mansion Mania Ep. 046: Verschollen
ags:mmm47                      Maniac Mansion Mania Ep. 047: Maniac Ostern
ags:mmm48                      Maniac Mansion Mania Ep. 048: Wendy und das Buch des Todes
ags:mmm49                      Maniac Mansion Mania Ep. 049: Clouso's grösster Coup
ags:mmm50                      Maniac Mansion Mania Ep. 050: The Date 3 / Das Date 3
ags:mmm51                      Maniac Mansion Mania Ep. 051: Place Machine II / Ortmaschine II
ags:mmm52                      Maniac Mansion Mania Ep. 052: Ein irrer Tag eines Ronvillers
ags:mmm53                      Maniac Mansion Mania Ep. 053: The Klaus strikes back / Der Klaus schlägt zurück
ags:mmm54                      Maniac Mansion Mania Ep. 054: CSI:RONVILLE
ags:mmm55                      Maniac Mansion Mania Ep. 055: Hamsters of the mysterious man: Chapter of dream
ags:mmm56                      Maniac Mansion Mania Ep. 056: Grotten-Urlaub
ags:mmm57                      Maniac Mansion Mania Ep. 057: Ein geheimnisvoller Ausflug
ags:mmm58                      Maniac Mansion Mania Ep. 058: The People's Court
ags:mmm59                      Maniac Mansion Mania Ep. 059: Computerliebe
ags:mmm60                      Maniac Mansion Mania Ep. 060: Jahrmarkt der Verdammten
ags:mmm61                      Maniac Mansion Mania Ep. 061: Bernard's Room
ags:mmm63                      Maniac Mansion Mania Ep. 063: Books - Deals unter Nachbarn
ags:mmm64                      Maniac Mansion Mania Ep. 064: Baranoia
ags:mmm65                      Maniac Mansion Mania Ep. 065: Save Smiley!
ags:mmm66                      Maniac Mansion Mania Ep. 066: Hoagies neuer Freund
ags:mmm66akt3                  Maniac Mansion Mania Ep. 066: Hoagies neuer Freund - Akt 3: Der verbotene Akt
ags:mmm67                      Maniac Mansion Mania Ep. 067: Die Schöne und das Biest
ags:mmm68                      Maniac Mansion Mania Ep. 068: MaMMa ante Portas
ags:mmm69                      Maniac Mansion Mania Ep. 069: Samstag
ags:mmm70                      Maniac Mansion Mania Ep. 070: Maniac Mansion Begins
ags:mmm71                      Maniac Mansion Mania Ep. 071: Neue Abenteuer auf Terra
ags:mmm72                      Maniac Mansion Mania Ep. 072: Mindbending TV
ags:mmm73                      Maniac Mansion Mania Ep. 073: Even a broken Clock
ags:mmm74                      Maniac Mansion Mania Ep. 074: Ted Edison and the Curse of King RootenTooten
ags:mmm75                      Maniac Mansion Mania Ep. 075: Das Necronomicon
ags:mmm76                      Maniac Mansion Mania Ep. 076: The Bernoulli-Show
ags:mmm77                      Maniac Mansion Mania Ep. 077: A Matter of Some Gravity / Schwer verquer
ags:mmm78                      Maniac Mansion Mania Ep. 078: Dumm geholfen
ags:mmm79                      Maniac Mansion Mania Ep. 079: Der Wunsch-O-Mat
ags:mmm80                      Maniac Mansion Mania Ep. 080: Spiel des Lebens
ags:mmm81                      Maniac Mansion Mania Ep. 081: Bernard bricht aus!
ags:mmm82                      Maniac Mansion Mania Ep. 082: Freundin mit Hindernissen
ags:mmm83                      Maniac Mansion Mania Ep. 083: Chasing Hoagie
ags:mmm84                      Maniac Mansion Mania Ep. 084: Surf'n'Ronville
ags:mmm85                      Maniac Mansion Mania Ep. 085: Freundin mit Hindernissen - Part 2
ags:mmm86                      Maniac Mansion Mania Ep. 086: Bernard bekommt Besuch
ags:mmm87                      Maniac Mansion Mania Ep. 087: Das Geheimnis des Blakes Hotel von Ronville
ags:mmm88                      Maniac Mansion Mania Ep. 088: Der alltägliche Wahnsinn
ags:mmm89                      Maniac Mansion Mania Ep. 089: Der Weltrettungsalgorithmus - Die neue Version
ags:mmm90                      Maniac Mansion Mania Ep. 090: Packing the suitcase / Kofferpacken
ags:mmm91                      Maniac Mansion Mania Ep. 091: Fels in der Brandung
ags:mmm92                      Maniac Mansion Mania Ep. 092: Project False Start
ags:mmm93                      Maniac Mansion Mania Ep. 093: Murder at the Moonshine Mansion
ags:mmm94                      Maniac Mansion Mania Ep. 094: Maniac on the Mississippi
ags:mmm95                      Maniac Mansion Mania Ep. 095: Britney's Escape / Britney's Flucht
ags:mmm96                      Maniac Mansion Mania Ep. 096: Dave's Home Odyssey
ags:mmm97                      Maniac Mansion Mania Ep. 097: Tollhaus-Weihnachten
ags:mmm98                      Maniac Mansion Mania Ep. 098: Maniac Apartment
ags:mmm99                      Maniac Mansion Mania Ep. 099: Die Premiere
ags:mmm100                     Maniac Mansion Mania Ep. 100: Money Mansion
ags:mmmatman                   Maniac Mansion Mania: @-Man - The Dork Knight
ags:mmmd1                      Maniac Dungeon Raum 01: The great Escape from Maniac Dungeon
ags:mmmd2                      Maniac Dungeon Raum 02: Der Bunker
ags:mmmd3                      Maniac Dungeon Raum 03: Der Verbindungstunnel
ags:mmmd4                      Maniac Dungeon Raum 04: Die Grotte
ags:mmmd5                      Maniac Dungeon Raum 05: Tief unter der Erde
ags:mmmd6                      Maniac Dungeon Raum 06: The Race
ags:mmmd7                      Maniac Dungeon Raum 07: Das unheimliche Wesen aus einem fremden Raum
ags:mmmd8                      Maniac Dungeon Raum 08: Die Brücke
ags:mmmd9                      Maniac Dungeon Raum 09: Und dann gab's wirklich, echt überhaupt gar keins mehr, ehrlich!
ags:mmmd10                     Maniac Dungeon Raum 10: Die neue Gefahr
ags:mmmd11                     Maniac Dungeon Raum 11: Die vergrabene Gruft
ags:mmmd12                     Maniac Dungeon Raum 12: Die Holozelle
ags:mmmd13                     Maniac Dungeon Raum 13: Der Trockenraum
ags:mmmd14                     Maniac Dungeon Raum 14: Vor der Tür
ags:mmmd15                     Maniac Dungeon Raum 15: Die unterirdische Kulturstätte
ags:mmmd16                     Maniac Dungeon Raum 16: Die U-Bahn-Station
ags:mmmd17                     Maniac Dungeon Raum 17: Wahnsinnsfahrt im Geisterzug
ags:mmmd18                     Maniac Dungeon Raum 18: Die perfekte Welle
ags:mmmd19                     Maniac Dungeon Raum 19: Weihnachts-Edition
ags:mmmd20                     Maniac Dungeon Raum 20: Die Pharaonen-Grabkammer
ags:mmmd21                     Maniac Dungeon Raum 21: Durch Raum (21) und Zeit
ags:mmmdasexperiment           Maniac Mansion Mania: Das Experiment
ags:mmmdieeroberung            Maniac Mansion Mania: Die Eroberung
ags:mmmeaster2010              Maniac Mansion Mania Easter: Ostereiersuche 2010
ags:mmmeaster2011              Maniac Mansion Mania Easter: Ostereiersuche 2011
ags:mmmeaster2018              Maniac Mansion Mania Easter: Ostereiersuche 2018
ags:mmmedgar1                  The Edgar Award Show - Staffel 1
ags:mmmedgar2                  The Edgar Award Show - Staffel 2
ags:mmmedgar2s2                The Edgar Award Show - Staffel 2 Show II
ags:mmmedgar3                  The Edgar Award Show - Staffel 3
ags:mmmedgar4                  The Edgar Award Show - Staffel 4
ags:mmmedgar5                  The Edgar Award Show - Staffel 5
ags:mmmedgar6                  The Edgar Award Show - Staffel 6
ags:mmmedgar7                  The Edgar Award Show - Staffel 7
ags:mmmedgar8                  The Edgar Award Show - Staffel 8
ags:mmmedgar9                  The Edgar Award Show - Staffel 9
ags:mmmhollywood               Maniac Mansion Mania Hollywood: Ronville Viper
ags:mmmhw1                     Maniac Mansion Mania Halloween 05-1
ags:mmmhw2                     Maniac Mansion Mania Halloween 05-2: Escape from Maniac Mansion
ags:mmmhw3                     Maniac Mansion Mania Halloween 05-3: Day of the Dead
ags:mmmhw4                     Maniac Mansion Mania Halloween 05-4: MMM-Horror
ags:mmmhw5                     Maniac Mansion Mania Halloween 05-5: Redrum
ags:mmmhw6                     Maniac Mansion Mania Halloween 06-1: The Curse of Maniac Mansion
ags:mmmhw7                     Maniac Mansion Mania Halloween 06-2: Hä? Ich glaub' ich spinne!
ags:mmmhw8                     Maniac Mansion Mania Halloween 10-1: Das Monster aus der Racoon Lagoon
ags:mmmhw9                     Maniac Mansion Mania Halloween 10-2: TMMCMFH
ags:mmmhw10                    Maniac Mansion Mania Halloween 10-3: Und Bernard läutet zur Geisterstunde
ags:mmmhw11                    Maniac Mansion Mania Halloween 10-4: Bad and Mad
ags:mmmlagrande                Maniac Mansion Mania: LaGrande Hotel
ags:mmmmm1                     Maniac Mansion Mania Mini Masterpieces Ep. 1: Eds Paket
ags:mmmmm2                     Maniac Mansion Mania Mini Masterpieces Ep. 2: Wendy im finsteren Keller
ags:mmmmm3                     Maniac Mansion Mania Mini Masterpieces Ep. 3: Harrys verwegener Tag
ags:mmmmm4                     Maniac Mansion Mania Mini Masterpieces Ep. 4: Berthold's Return / Bertholds Rueckkehr
ags:mmmmm5                     Maniac Mansion Mania Mini Masterpieces Ep. 5: Marcys Bestimmung
ags:mmmmovie1                  Maniac Mansion Mania Movies: Doktor in da House
ags:mmmmovie2                  Maniac Mansion Mania Movies: Doktor in da House II
ags:mmmmovie3                  Maniac Mansion Mania Movies: Kochen mit Fred und Ed
ags:mmmmovie4                  Maniac Mansion Mania Movies: The new president
ags:mmmmovie5                  Maniac Mansion Mania Movies: Doktor in da House III
ags:mmmmovie6                  Maniac Mansion Mania Movies: Just Maniac Mansion Mania
ags:mmmmovie7                  Maniac Mansion Mania Movies: 5th Maniac Birthday - Der Film
ags:mmmmovie8                  Maniac Mansion Mania Movies: Dinner for One
ags:mmmpolicemolest            Maniac Mansion Mania: Police Molest
ags:mmmtrash1                  Maniac Mansion Mania Trash: Frühjahrsputz
ags:mmmtrash2                  Maniac Mansion Mania Trash: Herrschaft der Futanaris
ags:mmmtrash3                  Maniac Mansion Mania Trash: Herrschaft der Futanaris 2
ags:mmmtrash4                  Maniac Mansion Mania Trash: Herrschaft der Futanaris 3
ags:mmmtrash5                  Maniac Mansion Mania Trash: Herrschaft der Futanaris 4
ags:mmmtrash6                  Maniac Mansion Mania Trash: NoGUI
ags:mmmtrash7                  Maniac Mansion Mania Trash: Iasons Testepisode
ags:mmmtrash8                  Maniac Mansion Mania Trash: MS: F**king Vista!
ags:mmmtrash9                  Maniac Mansion Mania Trash: Rettet Sandy
ags:mmmtrash10                 Maniac Mansion Mania Trash: Wink Smiley sucht den MMM-Millionär
ags:mmmtrash11                 Maniac Mansion Mania Trash: Jagd auf rotes Tentakel
ags:mmmtrash12                 Maniac Mansion Mania Trash: Run Hoagie Run
ags:mmmtrash13                 Maniac Mansion Mania Trash: Bernard muss mahl
ags:mmmtrash14                 Maniac Mansion Mania Trash: Bernard muss 2 mahl
ags:mmmtrash15                 Maniac Mansion Mania Trash: Wink Smiley sucht den MMMMillionär - Vol. II
ags:mmmtrash16                 Maniac Mansion Mania Trash: Wink Smiley sucht den Trashmillionär
ags:mmmtrash17                 Maniac Mansion Mania Trash: Wink Smiley sucht den MMMM - Bloody Halloween Version
ags:mmmtrash18                 Maniac Mansion Mania Trash: Bernard muss 3 mahl
ags:mmmtrash19                 Maniac Mansion Mania Trash: Bernard muss 4 mahl
ags:mmmtrash20                 Maniac Mansion Mania Trash: Britney muss mahl
ags:mmmtrash21                 Maniac Mansion Mania Trash: Smash The Tentacle
ags:mmmtrash22                 Maniac Mansion Mania Trash: Eine Traumepisode
ags:mmmwayne                   Maniac Mansion Mania: Wayne Shyster - Ace Attorney
ags:mmmxmas2008                Maniac Mansion Mania Christmas 2008: A Christmas Odyssey
ags:mmmxmas2015                Maniac Mansion Mania Christmas 2015: Three Days Before Christmas
ags:mobileangel                Mobile Angel
ags:moncul                     Mon Cul!
ags:moneycab                   Money Cab
ags:monkeyklon                 A Clone of Monkey Island
ags:monkeystothemoon           Monkeys to the Moon
ags:monkeywrench               Monkey Wrench Issue 1: Paying The Bills
ags:monsterfromthehountedhill  Monster from the hounted hill
ags:monsterwantsin             Monster Wants In
ags:montykomodo                Monty the Komodo dragon
ags:montyonthenorm             Monty on the Norm
ags:moonlightmoggy             Moonlight Moggy
ags:moorlandsonata             Moorland Sonata
ags:mooserage                  Moose Rage - part 1
ags:mooserage2                 Moose Rage - part 2
ags:mordy1                     Mordy: On Holiday
ags:mordy2                     Mordy 2: The Mirror of Truth
ags:moremonkeys                More Monkeys
ags:morganale1                 Morgan Ale, Case 1: Professor D
ags:morningshift               Morning Shift
ags:morphine                   Morphine
ags:mortifer                   Nous, les Mortifer
ags:motlpaa                    MOTLPAA
ags:mourirenmer                Mourir en Mer
ags:mouseoverslept             The Mouse Who Overslept
ags:moustachequest             Moustache Quest
ags:mrbeareng                  Mr. Bear Teaches English
ags:mrchocolate                The House of Mr. Chocolate
ags:mrdangerscontest           Mr. Danger's Contest
ags:mrfrisby                   Mr. Frisby Saves Xhristmas
ags:mrtijerakis                Mr. Tijerakis
ags:mudlarks                   Mudlarks
ags:murderdog4                 Murder Dog IV: Trial of the Murder Dog
ags:murdergrisly               Murder most grisly!!
ags:murderinawheel             Murder in a Wheel / Mord im Laufrad
ags:murderinminnesota          A Murder Mystery In Minnesota
ags:murderinthemansion         Murder in the Mansion
ags:murderofadrianelkwood      The Murder of Adrian Elkwood
ags:murphyssalvage1            Murphy's Salvage - Mission 01: Just My Luck
ags:murranchronicles1          Murran Chronicles - Episode 1: Jersey Devil
ags:murranchronicles2          Murran Chronicles - Episode 2: Talons of Terror
ags:murranchronicles3          Murran Chronicles - Episode 3: Lifedrinker of Landsdowne
ags:mushroomman                The Mushroom Man
ags:musicmixer                 Boyd's Music Mixer
ags:mutagen                    Mutagen
ags:muuyeeb                    MuuYeeb the Ghost
ags:mwhour                     Matt Wilson's Hour Game
ags:myburdentokeep             My Burden to Keep
ags:myfathersecret             My Father's Secret
ags:myfirstbigadv              My First Big Adventure
ags:myfirstquest               My First Quest
ags:mysterioushouse            Mysterious House
ags:mysterymeat                Mystery Meat Mayhem
ags:mysticseer                 Mystic Seer
ags:mythicalgambitflawlessfatality Mythical Gambit: Flawless Fatality
ags:nakedfear                  Naked Fear
ags:nanobots                   Nanobots
ags:nauticell                  Nauticell
ags:necroquest                 Necroquest - The Inheritance, Chapter 1
ags:nedysadventure             Nedy's Adventure: The curse of Vera
ags:nefasto                    Nefasto's Misadventure: Meeting Noeroze
ags:nekusnewtrip               Neku's new trip
ags:nellycootalot              Nelly Cootalot: Spoonbeaks Ahoy!
ags:neosaires2070              Neos Aires 2070: Sunday Comes First
ags:nerdyquest                 Nerdy Quest
ags:nesquest                   NES Quest
ags:neveralonehl               Never Alone Hotline
ags:neverlandmonopoly          Dread Mac Farlane: Neverland Monopoly
ags:newcity                    New City
ags:newkidgottasteal           New Kid Gotta Steal Somethin'
ags:news                       N.orth E.ast W.est S.outh
ags:nexttoevil                 Next to Evil
ags:nickitandrun               Al Gurbish in... Nick It & Run!!!
ags:niemandsland               Das Niemandsland
ags:nightandday                Night and Day
ags:nightmare                  Nightmare
ags:nightmareframes            Nightmare Frames
ags:nightoftheravingfeminist   Night of the Raving Feminist
ags:nightofthetesticle         Night of the Testicle
ags:nightwatch                 NightWatch (2008)
ags:nightwitch                 Night Witch
ags:nightwitches               Night Witches: Women of the clouds
ags:nightwork                  Nightwork
ags:ninatonnerre               Nina Tonnerre
ags:noactionjackson            No-Action Jackson
ags:noahsquest                 Noah's Quest
ags:nobodycares                Nobody Cares
ags:nodriver                   Welcome to Nod River
ags:nofear                     Where No Fear Was
ags:noiamspartacus             No, I Am Spartacus!
ags:noisymountain              Noisy Mountain
ags:nomonkeysbanana            No Monkey's Banana
ags:norbisquest                Norbi's quest
ags:norbisquest15              Norbi's quest 1,5
ags:norbisquest2               Norbi's quest 2
ags:norbiwinterspecial         Norbi winter special
ags:normalday                  Normal Day
ags:normancooks                Norman Cooks in: "Search for the Don"
ags:norserunereader            Norse Rune Reader
ags:nosferatu                  Nosferatu: Big City
ags:nostalgik                  NOSTALGIK
ags:notebookdetective          Notebook Detective
ags:notetoself                 Note to Self
ags:notexplainable             not the explainable
ags:notfine                    Not Fine
ags:notravellerreturns         No Traveller Returns
ags:noughtscrosses             Noughts & Crosses
ags:nsfware                    NSFWare
ags:ntgtfoi                    NTGTFOI - The Game
ags:nukemdukem                 NukemDukem Forever
ags:numberrescue               Number Rescue
ags:objectdreams               The Object of All Dreams
ags:obsession                  Obsession
ags:odottamaton                Odot Tamat On
ags:odow                       One Dungeon One Week
ags:odr3                       Outrage Dreamer Roads 3
ags:odr4                       Outrage Dreamer Roads 4
ags:officeshenanigans          Office Shenanigans
ags:offtheclock                Off The Clock
ags:ohdulieber                 Oh du lieber Augustin
ags:ohitschristmas             Oh, it's Christmas
ags:ohnonotagain               Oh no not again!
ags:oldmansea                  The Old Man and the Sea
ags:oldskies                   Old Skies
ags:omnipotenttarot            Omnipotent Tarot
ags:onceuponacrime             Once Upon A Crime
ags:onceuponatime              Once Upon A Time
ags:onceuponatime70s           Once upon a time in the '70s
ags:onceuponatimekeel          Once Upon a Time in Keel
ags:one                        One
ags:oneofthem                  One of them
ags:onemorefathom              One More Fathom
ags:oneofakind                 One of A Kind: a divine comedy of mistakes
ags:onerainyday                One Rainy Day
ags:oneroom                    One Room
ags:oneroomonecheese           One Room, One Cheese
ags:onespytoomany              One spy too many
ags:onethatremains             The One That Remains
ags:oneweekoneroom             One Week, One Room
ags:onleavingthebuilding       On Leaving The Building
ags:onlythegooddieyoung        Only The Good Die Young
ags:openquest                  OpenQuest
ags:operationforklift          Operation: FORKLIFT
ags:operationnovi              Operation Novi
ags:operationreddice           Operation: Red Dice
ags:operationsavebluecup       Operation Save Blue Cup
ags:orangeman                  The Orange man
ags:osd2                       Oceanspirit Dennis 2
ags:osd3d                      Oceanspirit Dennis 3D
ags:osdanish                   Oceanspirit Danish
ags:osdarayofhope              Oceanspirit Dennis: A Ray of Hope
ags:osdarchipelago             Oceanspirit Dennis - Archipelago Adventures 1
ags:osddeath                   The Death of Oceanspirit Dennis
ags:osdenise                   Oceanspirit Denise: Heroics In The Nick Of Time!
ags:osdfamous                  Oceanspirit Dennis Sorta 99% FAMOUS
ags:osdholiday                 Oceanspirit Dennis's Holiday Havoc!
ags:osdlastboss                Oceanspirit Dennis - Last Boss
ags:osdlgs                     Oceanspirit Dennis: Leather Gear Smooth
ags:osdlol                     LOL, Oceanspirit Dennis
ags:osdlostworld               Oceanspirit Dennis: The Lost World
ags:osdmancake                 A Taste of Man Cake
ags:osdmightypirate            Oceanspirit Dennis: Mighty Pirate
ags:osdmightyviking            Oceanspirit Dennis: Mighty Viking
ags:osdmoby                    Oceanspirit Dennis Moby GearWhaleDX
ags:osdninja                   Oceanspirit Dennis: The Naked & The Ninja
ags:osdocd                     Oceanspirit Dennis: The Full Name Of This Game Won't Fit In The Subject Line!!1
ags:osdpoop                    Oceanspirit Dennis: Pirates on the Poopdeck!
ags:osdprincess                Oceanspirit Dennis: The Terror of the Ice Princess
ags:osdrots                    Oceanspirit Dennis: Rise of the Spirit
ags:osdrpg                     Oceanspirit Dennis: The RPG
ags:osdscourge                 Oceanspirit Dennis: Scourge of the Underworld
ags:osdscourgehd               Oceanspirit Dennis: Scourge of the Underworld HD
ags:osdsearch                  The Search for Oceanspirit Dennis
ags:osdshindig                 The Shindig of Dennis
ags:osdsquares                 Oceanspirit Dennis: [][][][][][][][][]
ags:osdsweet                   Oceanspirit Dennis: Sweet Revenge
ags:osdtextual                 Oceanspirit Dennis Gets Textual
ags:osdvaginity                Oceanspirit Dennis LOSERS HIS VAGINITY
ags:osdvscloud                 Oceanspirit Dennis vs. Cloud Strife
ags:osdvsron                   Oceanspirit Dennis vs. Reality-on-the-Norm
ags:osdwetspot                 Oceanspirit Dennis: The Wet Spot
ags:osher                      Boundless Osher / Osher Bli Gvulot
ags:ossuarium                  Ossuarium
ags:otakurivals                Otaku Rivals
ags:otherworlds                Other Worlds
ags:otisbuildsafire            Otis Builds a Fire
ags:ourfinesthour              Our Finest Hour
ags:ouroborossacrifice         Ouroboros: The Sacrifice
ags:ourobouros                 I am Ourobouros
ags:outbreak                   Outbreak
ags:outbreakwarehouse          Outbreak: The Warehouse
ags:outofgas                   Out of Gas
ags:outscore                   Outscore
ags:outtajuice                 Outta' Juice
ags:overroger                  Over Roger
ags:overtheedge                The Journey Down: Over the Edge
ags:owlhunt                    Owl Hunt
ags:owlsquest                  Owl's Quest: Every Owl has its Day
ags:ozorwell1                  Oz Orwell and the Crawling Chaos
ags:ozorwell2                  Oz Orwell and the Exorcist
ags:palacin                    Palacin
ags:palettequest               Palette Quest
ags:palettequest2              Palette Quest 2.0
ags:pandainspace               Panda In Space
ags:pandor                     Pandor
ags:paperkubik                 Lost in the Tomb / Paper-Kubik
ags:paperplanes                Paper Planes
ags:paradiselost               Larrywilco in: Paradise Lost
ags:parameciumcomplex          The Paramecium Complex
ags:paramnesia                 Paramnesia
ags:paranoid                   Paranoid!
ags:paranormalinvestigation    Paranormal Investigation
ags:party                      Party
ags:patchwork                  Patchwork
ags:pathskinwalker             Path of the Skinwalker
ags:paulainwonderland          Paula in Wonderland
ags:paulmooseinspaceworld      Paul Moose In Space World
ags:paulquest                  Paul Quest Gold Edition
ags:paulromano                 Paul Romano - Recollection 1
ags:peakvalley1                Mysteries of Peak Valley 1 - The Lost Sonata
ags:peakvalley2                Mysteries of Peak Valley 2 - The White Lady
ags:pendek                     Pendek
ags:pengaobcster               Penga & Obcster's Christmish Adventure
ags:pennispong                 Pennis: The Ultimate in Pong!
ags:pepeadventure              Pepe's Little Adventure
ags:perceptions                Perceptions
ags:perelman                   Perelman
ags:perilsofpoom               Perils of Poom
ags:personalrocket             Personal Rocket
ags:pesterquest                Pester Quest: From n00b to newb
ags:petshopincident            The Pet Shop Incident
ags:petalrose                  Petals Around the Rose
ags:pharmacistjones            Pharmacist Jones
ags:philococoa                 Philosophers Like Hot Cocoa
ags:phoenix1                   Phoenix1
ags:pickpocketrpg              Pickpocket RPG
ags:piginapoke                 Pig in a poke
ags:pilotlight                 Pilot Light
ags:pimpinonparakuss           Pimpin On Parakuss IV
ags:pinkcult                   Rex and Sissi in Pink Cult
ags:pinksky                    Pink Sky
ags:piratefry2                 Pirate Fry 2: The Hand of Anturus
ags:piratefry3                 Pirate Fry 3: The Isle of the Dead
ags:pirates                    Pirates!
ags:piratescaribbean           Pirates of Monkey Island of the Caribbean
ags:piratess                   Piratess - Season of the Silver Moon
ags:piss                       PISS
ags:pixel                      PIXEL
ags:pixelhunt2005              Pixel Hunt (2005)
ags:pixelhunt2007              Pixel Hunt (2007)
ags:pixia                      PiXiA: Rainbow of Havoc
ags:pixxxelhunter              Pixxxelhunter: The Epic
ags:pizzacalls                 Pizza Calls
ags:pizzanostra                Pizza Nostra
ags:plan10frommypants          Plan 10 from MY PANTS!!!
ags:planetxmas                 Planet Xmas
ags:planm                      Plan M
ags:plantsimulator             Plant Simulator
ags:platformerius              Platformerius - The Ninja Incident!
ags:platformhorde              Platform Horde
ags:playitagain                Play It Again: An Improv Point And Click Adventure
ags:playxylo                   Play Xylophone & Singing Cat
ags:pledgequest1               Pledge Quest I: The SpaceVenture Adventure
ags:pledgequest2               Pledge Quest II: Noodle Shop of Horrors
ags:pleurghburgdarkages        Pleurghburg: Dark Ages
ags:plumberboy                 PlumberBoy
ags:pmquestions                Prime Minister's Questions: The Game
ags:pmuvchvt                   PMUVCHVT
ags:pocketfluff                PocketFluff! Yay!
ags:pocketquest                Pocket Quest
ags:poeng                      POEng'n'Klik
ags:politicalenemy             Political Enemy
ags:politicallyyours           Politically Yours
ags:pompadourpete              Pompadour Pete On The Road To Goblin Keep
ags:ponderabilia               Ponderabilia
ags:pong                       PONG
ags:postmansquest              Postman's Quest - Not Rain nor Sleet nor ARMAGEDDON
ags:potatohead                 Potato Head: Sweet Attack!
ags:potionmagique              La Potion Magique
ags:potionmaster               The Potion Master
ags:poudlardmotus              Poudlard Motus
ags:pouvoir                    pouvoir
ags:powernap                   Power Nap
ags:powerunlimited             Power Unlimited Boardgame
ags:pqtadventure               Adventures of PQT
ags:practicescript             Practice Script: The 1-Room Puzzler
ags:predatorspreyforplants     Predators Prey For Plants
ags:preludetoadventure         A Prelude to an Adventure
ags:preptime                   Prep Time
ags:priderelatives             Pride & Relatives
ags:princedickless             Prince Dickless
ags:princeoflordenp1           The Lost Prince Of Lorden - Part 1
ags:princessandallthekingdom   The Princess and all the Kingdom
ags:princessmarian1            The Marvellous Adventures of Princess Marian
ags:princessmarian2            The Marvellous Adventures of Princess Marian part II: Mother's Day
ags:princessmarian3            The Marvellous Adventures of Princess Marian part III: Happy Birthday Little Flower
ags:princessmarian4            The Dark Cave: Adventures of Princess Marian part IV
ags:princessmarian5            Alba the Explorer: Princess Marian part V
ags:princessmarian6            Princess Marian and the Fountain of Unicorns (Princess Marian part VI)
ags:princessmarian7            C.U.T.E. (Princess Marian VII)
ags:princessmarian8            Princess Marian VIII: Snow Fight!!!
ags:princessmarian9            Princess Marian and The Phantom of the Ballet (Princess Marian IX)
ags:princessmarian10           The Adventures of Princess Marian part X: Magic Hat
ags:princessmarian11           Princess Marian XI: Light Re-leaf
ags:princessmarianspigeonpinger Princess Marian's Pigeon Pinger
ags:principlesofevil           Principles of Evil
ags:principlesofevil2          Principles of Evil II: Misery Loves Company
ags:privatedetective           Private Detective
ags:procrastinator             Procrastinator
ags:prodigal0                  Prodigal 0
ags:prodigal                   Prodigal
ags:prodigalshooter            Prodigal Shooter
ags:profneely                  Professor Neely And The Death Ray Of Doom
ags:projectevilspy2            Project Evilspy II
ags:projectlazarus             Project Lazarus
ags:projectmadness             Project Madness
ags:proofoffiction             Proof of Fiction
ags:proposal                   Proposal
ags:prototypical               Prototypical
ags:providence                 Providence
ags:proxecto                   Proxecto Percebe
ags:psychofb                   Psycho Flashback
ags:psychopomp                 Psychopomp
ags:pubmasterquest             Pub Master Quest
ags:pubmasterquest2            Pub Master Quest II - Shogin Crystal
ags:puddypenguin               Puddy Penguin
ags:purgatorio                 Purgatorio
ags:purityofthesurf            Purity of the Surf
ags:purposeretired             Purpose : Retired
ags:pussiehunt                 Pussie Hunt
ags:puzzlepumice               Puzzle of the Pulchritudinous Pumice
ags:puzzlebots                 Puzzle Bots
ags:pxenophobe                 Project Xenophobe
ags:questfighter               Quest Fighter
ags:questfighter2              Quest Fighter II
ags:questforcinema             Quest For Cinema
ags:questforjesus              Quest for Jesus
ags:questforthebluecup         Quest for the Blue Cup
ags:questforyeti               Quest for Yeti
ags:questforyrolg              Quest for Yrolg
ags:quietgame                  The Quiet Game
ags:quimbyquestanewdope        Quimby Quest I: A New Dope
ags:quiteannoying              The Quite Annoying League
ags:rabbiteyemotel             An Evening At The RabbitEye Motel
ags:rabbithill                 Rabbit Hill
ags:race                       R.ACE
ags:racingmanager              AS Racing Manager
ags:racist                     Racist
ags:rackham                    Rackham
ags:rainblood                  Rain of Blood
ags:rainbowskunk               Rainbow Skunk Prism and the Vermin-Truder
ags:rainbowtube                Billy And Desmond's Fantastic Amazing Rainbow Tube
ags:rainsnow                   Rain & Snow - The Bouncer
ags:ralphtheraven              Ralph the Raven
ags:ramghost                   RAM Ghost
ags:ramsesporter               Ramses Porter and the Relay for Love
ags:rango                      Rango
ags:rapsqlud                   RapSqLud
ags:rapstar15                  Rapstar 1.5
ags:ratchannel                 Rat Channel
ags:ratpackcastle              The Rat Pack Do Cheesy Castle
ags:ratplaying                 Rat Playing Game
ags:ravench1                   Raven - Chapter 1: The Commands of Eurybia
ags:rayandtheguitar            Ray and the Guitar
ags:raybexter                  Ray Bexter
ags:raysrods                   Ray's Rods
ags:razorsinthenight           Razors in the Night
ags:rcpd                       Robot City Police Department
ags:reactor09                  Reactor 09
ags:readyeddie                 READY starring Ready Eddie
ags:reagentorange              Re-Agent Orange
ags:realitycheck1              Reality Check
ags:realitycheck2              Reality Check 2
ags:realitycheck3              Reality Check 3
ags:realitycheck4              Reality Check 4
ags:realityinthenorm           Reality-in-the-Norm
ags:recess                     Recess
ags:recess2                    Recess 2
ags:recollection               Recollection
ags:redbeardsavesron           Red Beard Saves Reality-on-the-Norm
ags:reddwarf                   Red Dwarf
ags:redflaggredux              Red Flagg in: Don't Call me Blue! REDUX
ags:redhotoverdrive            Red Hot Overdrive
ags:redpantsep1                The Adventures of Redpants: The Princess and the Beanstalk
ags:redpantsep2                Redpants Meets Robinson Clauseau
ags:reefriversquestforekoban   Reef Rivers: Quest for Ekoban
ags:rein                       rein
ags:rend                       The Tapestry - Chapter 2: Rend
ags:renuncio                   Renuncio!
ags:renuncio2                  Renuncio: Parte 2 - El Escape
ags:reonquestep1               Reon Quest Ep. I: The Mysterious Aluminatti Society
ags:reonquestep2               Reon Quest Ep. II: Escape From Bully Island
ags:repossessor                The Repossessor
ags:requiem                    Requiem
ags:researchreservations       Research Reservations
ags:researchresident           Research Resident
ags:retaliation                Reality-on-the-Norm 13:13 Retaliation
ags:retroron                   Retroron
ags:returnjourney              Return Journey
ags:returntocivilization       Return To Civilization
ags:revelation                 Revelation
ags:revenants                  Revenants
ags:rickyquest                 Ricky Quest
ags:righteouscityp1            Righteous City - part I
ags:righteouscityp2            Righteous City - part II
ags:ripperjack                 Ripper Jack
ags:rnbquest                   R'n'B Quest
ags:roadbrollywood             Road to Brollywood
ags:roadofdestiny              Road of Destiny
ags:roadracer                  Road Racer
ags:roastmothergoose           Roast Mother Goose
ags:robbingtheprincess         Robbing The Princess
ags:robertredford1             Robert Redford Saves The Day Ep. 1: Getting There
ags:robertredford2             Robert Redford Saves The Day Ep. 2: The Pit and the Pendulum
ags:robertredford3             Robert Redford Saves The Day Ep. 3: Who Framed Roger Redford
ags:robmassacreofchainsawness  Rob: The Massacre of Chainsawness
ags:robolution                 Robolution
ags:roboquest                  Robo Quest
ags:roboquest2009              ROBO-QUEST 2009
ags:robotragedy                Robotragedy
ags:robotragedy2               Robotragedy 2 - Countdown To Doomsday
ags:robotsdream                Do Robots Dream of Ice Cream?
ags:roccioquest                Roccio Quest
ags:rockabillykid              Rockabilly Kid
ags:rockatruestory             Rock - A True Story
ags:rockburgerstreehouses      Rock Burgers & Tree Houses
ags:rockpaperscissors2         Rock, Paper, Scissors! Reboot
ags:rockrockrock               Rock Rock Rock
ags:rockyroams                 Rocky roams
ags:rodequest2                 Rode Quest 2: The Sweet Smell of Stenchie
ags:rogered                    Rogered
ags:rogeroddsp1                Roger Against The Odds - Part 1: Trapped in the lab
ags:rogerquest                 Roger's Quest
ags:rogue                      Rogue
ags:ron5thanniversary          Reality-on-the-Norm 5th Anniversary Trailer
ags:ronbeforethelegacy         Reality-on-the-Norm: Before the Legacy
ags:ronoutbreak                The Outbreak (Day of Comet)
ags:ronsixteen                 Sixteen
ags:rontimeouttrailer          Time Out Trailer
ags:rootofallevil              Root of All Evil
ags:rosauradocelestial         Rosaura Docelestial: Rescue from Despair
ags:rosellahelm                Rosella Wilson Meets Helm
ags:rotla                      Riders of the Lost Ark
ags:rowengoestowork            Rowen Goes To Work
ags:rtmi                       Return to Monkey Island
ags:rudeawakening              Rude Awakening
ags:rufusstory                 Rufus' Story
ags:runaway                    RunAway
ags:runestones                 Runestones!
ags:ruptquest                  Rupt Quest
ags:ryansdayout                Ryan's Day Out
ags:sabotagenb                 Sabotage on Noegato-Bas
ags:saddsonissein              Saddson Issein
ags:salazarsevilplan           Salazar's Evil Plan
ags:samarkand                  Samarkand
ags:sammysperm                 Sammy Sperm
ags:sammysquest                Sammy's Quest
ags:sandiknievel               Sandi Knievel: Stunt Rider
ags:sandmen                    Sandmen
ags:santaclausdown             Santa Claus Down
ags:santaflight                Santa Claus in A Flight To Remember
ags:santaorphanage             Santa and the orphanage
ags:santassidekick             Santa's Sidekick
ags:santasstolensleigh         Santa's Stolen Sleigh
ags:sarmanyanha                The Manuscripts of Sarmanyanha
ags:satanquest                 Satan Quest
ags:satchsquest                Satch's Quest
ags:saturdaynightlone          Saturday Night is the Loneliest Night of the Week
ags:saturdayschool             Saturday School
ags:saturdaysymbiosis          Saturday Night Symbiosis
ags:saw                        Saw
ags:saw2                       Saw II
ags:sawn1                      Sawn 1: Pain is just the start!
ags:scalestraining             Scales Training Game
ags:scarecrowquest             Scarecrow and his quest for a brain
ags:scaredstiff                Scared Stiff
ags:scarymaze                  Scary Maze Halloween 2016
ags:scenario5b                 Scenario 5B
ags:schnelltrial               The Trial of the Schnellersparrow
ags:schoollout                 Schoollout
ags:science                    Science!
ags:sciencesfaer               Les Sciences du Faër
ags:scnidersom                 Scnidersom
ags:scotchanimation            Scotch's Animation Demo
ags:scramschool                Scram School 3 Challenge 17: "Petezah Time III: Petezah in Space"
ags:scrapmanager               S.A.M. - Scrap Allocation Manager
ags:screamingsouls             Screaming Souls
ags:scumpub                    Scum Pub
ags:scyllacharybdis            Scylla and Charybdis: A Grecian Ship From Olympus U
ags:scytheisland               Scythe Island
ags:searchforsanity            Search for Sanity
ags:searchofmarina             In search of Marina
ags:seashells                  Seashells
ags:seasongreetings2002        Season Greetings 2002
ags:secondplace                Second Place is for Losers
ags:secondstime                Seconds Time's the Charm
ags:secretquestremake          Secret Quest Remake
ags:secrets                    Secrets
ags:seed                       Seed
ags:self                       Self
ags:sepulchre                  Sepulchre
ags:serina                     Serina's Transylvanian Trip
ags:serum                      Serum
ags:sevendoors                 The Seven Doors
ags:sevgilim                   Sevgilim Olur musun?
ags:shadesofgreye              Shades of Greye
ags:shadowgate                 Shadowgate Remake
ags:shadowsofron               Shadows of Reality-on-the-Norm
ags:shadowsoftheempire         Star Wars: Shadows of the Empire - Graphic Adventure
ags:shailadusithlenquete       Shai-la du Sith : l'Enquete / The Investigation
ags:shailaofthesith            Shai-la of the Sith / Shai-la du Sith
ags:shamrockhg                 Shamrock High Graduation
ags:shapeshift                 Shapeshift for Cheese
ags:shapevillage               Shape Village
ags:sharethis                  Share This With Your Friends
ags:sharkysthree               Sharky's 3: The Heist
ags:shawshank                  The Shawshank Redemption
ags:sheepquest                 Sheep Quest
ags:sheetart                   Sheet: The art of Art
ags:shemwood                   Shemwood Plains
ags:sherlock                   Sherlock - The Dark Arts
ags:shifter                    Shifter
ags:shifters                   Shifters
ags:shiftersboxoutsidein       Shifter's Box - Outside In
ags:shittyquest                Shitty Quest
ags:shootabducted              Shoot, I Got Abducted!
ags:shootinggame               The Shooting Game
ags:shootmyvalentine           Shoot My Valentine
ags:shortcut                   ShortCut
ags:shrivel                    Shrivel
ags:shunday                    Shunday
ags:sierraquest1               Sierra Quest 1: Roberta in Love
ags:signalloss                 Signal Loss
ags:silentknight1              Silent Knight - Chapter One: The Mediocre Escape
ags:silentknight2              Silent Knight - Chapter Two: The Conscience of the King
ags:simonsjourney              Simon's Journey
ags:simonthesorcerer3          Simon the Sorcerer 3
ags:simonthesorcerersbrother   Simon, The Sorcerer's Brother
ags:simshogwarts               Sims Hogwarts
ags:sinbad                     Sinbad - The Island of Korkus
ags:sinking                    Sinking
ags:sisterhelper               Sister's Little Helper
ags:sisyphus                   Sisyphus Reborn
ags:skippysavestheday          Skippy Saves The Day
ags:skumring                   Skumring
ags:skyadventure               Sky Adventure
ags:skyfall                    Skyfall
ags:slaythedragon              Slay the Dragon
ags:slaythedragon2             Slay the Dragon II
ags:slaythedragon3             Slay the Dragon III
ags:sleepingbeauty             Sleeping Beauty
ags:sleepyisland               The Sleepy Island
ags:sleuth2020remake           SLEUTH Remake
ags:sleuthch1                  Sleuth - Chapter One
ags:slidersquest               Sliders Quest
ags:slimequestforpizza         Slime Quest for Pizza
ags:slothforseasons            A Sloth For Both Seasons
ags:slugprincess               Slug Princess
ags:sma2                       Second Moon Adventure - Part II: White Moon or Red Moon
ags:sma3                       Second Moon Adventure - Part III: Rest In Peace
ags:sma4                       Second Moon Adventure - Part IV: Abendmond
ags:sma5                       Second Moon Adventure - Part V: Next Evolution
ags:sma6                       Second Moon Adventure - Part VI: Mysterious Time Travel
ags:sma7                       Second Moon Adventure - Part VII: Ocean Life
ags:sma8                       Second Moon Adventure - Part VIII: Ungewisse Herkunft
ags:sma9                       Second Moon Adventure - Part IX: Zwei Welten in Einer
ags:sma10                      Second Moon Adventure - Part X: Walder Hier Und Dort
ags:sma11                      Second Moon Adventure - Part XI: Jahrtausendwende
ags:smgilbert                  Sam & Max - Il caso Gilbert
ags:smileysquest               Smiley's Quest
ags:smileysquest2              Smiley's Quest 2
ags:smokinweed                 Smokin' Weed
ags:smoothhide                 Smooth Hide
ags:snake                      Snake
ags:snakesofavalon             Snakes of Avalon
ags:snakesonaplane             Snakes on a plane!
ags:snipermotherland           Sniper and spotter serving the motherland
ags:sniperpatriotic            Sniper and spotter being patriotic
ags:snipertower                Sniper and spotter climbing a tower
ags:snowmaneatcarrot           May the Best Snowman Eat a Carrot
ags:snowqueen                  The Snow Queen: After the Apocalypse
ags:snowtheadventure           SNOW - The Adventure Game
ags:sockstoday                 Should Have Worn Socks Today
ags:solitude                   Solitude
ags:somethingnovel             Something Novel
ags:somewhere                  Somewhere
ags:somnamulizer               Somnamulizer: A Tale From Olympus U
ags:songanimals                Song Animals
ags:sonicandfriendsinclubhouse Sonic and friends in: Club House
ags:sophiamcgrath              Sophia McGrath and the Strange Invitation
ags:sorenquest                 Soren's Quest
ags:sosk                       Secrets of Sultan Kanuni
ags:soulsquest                 Souls Quest
ags:sovietunterzoegersdorf1    Soviet Unterzögersdorf: Sector I
ags:sovietunterzoegersdorf2    Soviet Unterzögersdorf: Sector II
ags:spacebirdmissile           Space Bird Missile Cats
ags:spacecatvirus              Space Cat vs. Virus
ags:spacecross                 Space Cross: The BSG-Team
ags:spacefreakers              Space Freakers
ags:spacegremlin               Space Gremlin
ags:spacehunter                Space Hunter
ags:spacelynxes                Space Lynxes
ags:spacemanspace              Spaceman in Space
ags:spacemaze                  Space Maze
ags:spacepirates               Space Pirates
ags:spacepoolalpha             Space Pool Alpha
ags:spacerangersep46           Space Rangers S.O.B. Ep. 46: The Devil Within
ags:spacerangersep52           Space Rangers S.O.B. Ep. 52: The Redemption of Grisli Adams
ags:spacesim                   Space Sim - AGS 3D
ags:spacetrash                 Space Trash
ags:spacetunneler              Space Tunneler
ags:spacewarep1                Space War - Episode 1: The Crystal
ags:spacewarep2                Space War - Episode 2: Curien Strikes Back
ags:speedbuggy                 Speed Buggy: Manifold Destiny
ags:spellbound                 Spellbound: A Clive Mandrake Adventure
ags:spidertrek                 Spider Trek
ags:spilakassinn               Spilakassinn - The Slot Machine
ags:spiritboard                Midnight Spirit Board
ags:spitboy                    Spit Boy
ags:splinter                   Splinter
ags:splitfighters              Split Fighters
ags:spmachinima1               SP Machinima - Episode 1
ags:spmachinima2               SP Machinima - Episode 2
ags:spooks                     Spooks
ags:spoonsiii                  Spoons III - The Unauthorized Edition
ags:spottd_boyd                Spot The Difference (2003)
ags:spottd_captaind            Spot The Difference (2015)
ags:sproutsofevil              Sprouts of Evil
ags:sq2svga                    Space Quest II SVGA Remake
ags:sq3vga                     Space Quest III VGA Preview
ags:sq45                       Space Quest IV.5 - Roger Wilco And The Voyage Home
ags:sq55                       Space Quest 5.5: Save Captain Roger
ags:sq7m1                      Space Quest 7 Mania Ep. 1
ags:sq7m2                      Space Quest 7 Mania Ep. 2
ags:sqdote                     Space Quest Minus 1: Decisions of the Elders
ags:sqdote2                    Space Quest: A Son of Xenon
ags:sqinc                      Space Quest: Incinerations
ags:sqkubik                    SQ Kubik
ags:sqm11                      Space Quest Mania 1x1
ags:sqm12                      Space Quest Mania 1x2
ags:sqm13                      Space Quest Mania 1x3
ags:sqm14                      Space Quest Mania 1x4
ags:sqm15                      Space Quest Mania 1x5
ags:sqm16                      Space Quest Mania 1x6
ags:sqos                       SQ Online Strike
ags:sqpotim                    Space Quest: Planet of the Incredible Menace
ags:sqvn                       Space Quest Visual Novel
ags:sqvsb                      Space Quest: Vohaul Strikes Back
ags:sram2                      SRAM 2 - Cinomeh's Revenge
ags:stablepeteandthejoust      Stable Pete and the Joust
ags:stairquest                 Stair Quest
ags:stanamespiepisode1         Stan Ames, Private Eye - Episode 1: Murder Incorporated
ags:stansrevenge               Stan's Revenge
ags:starfreakers               StarFreakers
ags:stargateadv                Stargate Adventure
ags:stargatequizz              Stargate Quizz
ags:stargatesgc                Stargate SGC
ags:stargatesolitaire          Stargate Solitaire
ags:starlitgrave               Starlit Grave
ags:starshipcaramba            Starship Caramba
ags:starshiphindenburg         Last Flight of the Starship Hindenburg
ags:starshiplight              Starship Light
ags:starshipposeidon           Starship Poseidon - Part 1
ags:startrekgalactique         Star Trek - Aventure Galactique
ags:startrekmansion            Star Trek - Back To The Mansion
ags:startrekmission            Star Trek Mission
ags:startreknewton             Star Trek Newton - Part One: Anomaly
ags:startropy                  Startropy
ags:stateofmind                State of Mind
ags:steamedhams                Steamed Hams: The Graphic Adventure
ags:steamsquares               Steamsquares
ags:steamtrek                  Steam Trek: Clueless around Risa
ags:stediddyip1employment      Stediddy in IP1 - Employment
ags:stellarmessep1             Stellar Mess - Episode 1: The Princess Conundrum
ags:stephenkingcars            Stephen King DodgeEmCars
ags:stevequest                 Steve Quest
ags:stickmanrpg                Stickman RPG
ags:stickmenterrorists         Stickmen in the land of the terrorists
ags:stickycrimsonhouse         Sticky the Stick Figure Part 1: The Crimson House
ags:stolenmoustache            The Case of the Stolen Moustache
ags:stormpuncher               Not My First Apocalypse: Stormpuncher
ags:stranded                   Stranded
ags:strangerbynight            Stranger by Night
ags:strangerinstickworld       Stranger in Stickworld
ags:strangerthings             Stranger Things
ags:strawmanaugment            The Strawman Augment
ags:strawmanbomb               Strawman Bombing Disposal
ags:stuckathome                Stuck at Home
ags:stuckinamuddle             Stuck in a Muddle with You
ags:stuckonyou                 Stuck on you
ags:studiomediocre             Studio Mediocre: The Case of the Bedeaded Dramatist
ags:subatomic                  subAtomic
ags:subterra                   Subterra
ags:subwaycrisis               Subway Crisis
ags:suenanfantasmas            ¿Sueñan Los Fantasmas?
ags:summerwoes                 Summer Woes
ags:sunriseparadise            Sunrise Paradise
ags:supaevil                   Supa-EviL
ags:superegoch0                Superego - Chapter 0
ags:supergirl                  Supergirl in: We Don't Need Another Hero
ags:superhammerquest           Super Hama Queste
ags:superpitstopracing         Super Pitstop Racing
ags:suppaninja                 Suppa Ninja
ags:surreality                 Surreality
ags:suspiciousmind             Suspicious Mind
ags:svengordan1                Sven Gordan, Paranormal Parody - Case 1: In search of Big Apes
ags:sweetmythery               Sweet Mythery
ags:swordremake                Sword - The First Remake
ags:sydneyfindsemployment      Sydney Finds Employment
ags:sydneytreadsthecatwalk     Sydney Treads the Catwalk
ags:symbiosis                  Symbiosis
ags:syncroutine                sync::routine
ags:tablarawls                 La Tabla de Rawls
ags:tabletsoftibet             The Sacred Tablets of Tibet
ags:tactician                  Tactician: Civil War
ags:taleofalegacy              A Tale of a Legacy / En busca de un legado
ags:talesfromtheroad           Tales From the Road
ags:talesofchickenry           Tales of Chickenry
ags:talesofjayvin              Tales of Jayvin
ags:talesofotubania            Tales of Otubania
ags:taospacetime               Tao Through Space and Time
ags:tarthenia                  Tarthenia
ags:tasteblood                 Taste the blood of darkness
ags:tattooroom                 The Tattoo Room
ags:teafortwo                  Tea for Two - A Detective Logan Case
ags:technobabylonp3            Technobabylon - Part 3: In Nuntius Veritas
ags:tedmcbinky                 Ted McBinky and his Steam Engine
ags:tehhorror                  Teh Horror!
ags:templeofspheres            Indiana Jones and the Temple of Spheres
ags:tenhumstombpart1           Tenhum's Tomb Part 1
ags:terrorofthevampire         Terror of the Vampire!
ags:teruteru                   Teru Teru Bozu
ags:tetricity                  TetriCity
ags:textparsergame             Text Parser Game
ags:tfg-bttf                   The Fan Game - Back to the Future - Interactive Adaptation
ags:tfg-bttf3                  The Fan Game - Back to the Future Part III: Timeline Of Monkey Island
ags:tfg-bttf4                  The Fan Game - Back to the Future Part IV: The Multitasking Crystal
ags:tfg-bttf5                  The Fan Game - Back to the Future Part V: Multidimensional Space-Timelines
ags:tfg-bttfwat                The Fan Game - I'll Be Back to the Future With A Terminator
ags:tfg-mi                     The Fan Game - Ghostbusters and The Secret of Monkey Island
ags:tfg-goonies                The Fan Game - The Goonies
ags:tfg-pixel                  The Fan Game - The Pixel Has You - Disk 1
ags:tfg-somi                   The Fan Game - The Secret of Monkey Island - RECODED
ags:tfg-ssgw                   The Fan Game - Saint Seiya - Galaxian Wars
ags:tfg-zak2                   The Fan Game - Zak McKracken: A Mansion, a Meteor and the Alien Mindbenders
ags:tftoz1                     Tales From The Outer Zone: Cyborg Seppuku
ags:tftoz2                     Tales From The Outer Zone: The Goat Crone
ags:tftoz3                     Tales From The Outer Zone: Fleshworms
ags:tftoz4                     Tales From The Outer Zone: The Construction
ags:tharsheblows               Thar she blows!
ags:thatcrazyworld             That Crazy World
ags:thatdamndog                THAT DAMN DOG!
ags:thatday                    That Day
ags:the30minutewar             Duke Stanley, National Hero in: The 30 Minute War
ags:the4thwall                 The 4th Wall﻿
ags:the7thsense                The 7th Sense
ags:theabtyoncase              Tales from the Eureka Cluster : The Abtyon Case
ags:theaddict                  The Addict
ags:theadventureofthehero      The Adventure of the Hero
ags:theadventuresofturquoise   The Adventures of Turquoise MacDonald
ags:theartifact                The Artifact
ags:theaspiroxcase             The Aspirox Case / L'Affaire Aspirox
ags:theassassin                The Assassin
ags:theawakening               The Awakening
ags:thebadneighbours           The bad neighbours
ags:thebar                     The Bar
ags:theblock                   The Block
ags:thebrokenbrain             The Broken Brain
ags:thebum                     The Bum
ags:thebunker                  The Bunker
ags:theburgerflipper           The Burger Flipper
ags:theburgomaster             The Burgomaster
ags:thebutler                  The butler didn't do it
ags:thecabin                   The Cabin
ags:thecadaversynod            The cadaver synod
ags:thecan                     The Can
ags:thecatcase                 The Cat Case
ags:thecatsman                 The Man Who Liked Cats
ags:thecell2005                The Cell (2005)
ags:thecell2017                The Cell (2017)
ags:thechronomancers           The Chronomancers
ags:thechrysalis               The Chrysalis
ags:thecityadv                 The City Adventure
ags:thecomingofage             The Coming of Age - a Lorna Bains whodunit
ags:thecondemned               The Condemned
ags:thecradle                  The Cradle
ags:thecrazedchicken           The Crazed Chicken
ags:thecube                    The Cube
ags:thecurseoflife             The Curse of Life
ags:thedarkplague              The Dark Plague
ags:thedarktrial               The Dark Trial
ags:thedayafter                The day after you went away
ags:thedaynothinghappened      The Day Nothing Happened
ags:thedayofdarkness           The Day Of Darkness
ags:thedeathoflukesimpson      The Death of Luke Simpson
ags:thedecorcist               The Decorcist
ags:thedeed                    The Deed
ags:thedevilsshroudpart1       The Devil's Shroud - Part I
ags:thedevilsshroudpart2       The Devil's Shroud - Part II
ags:thedevilsshroudpart3       The Devil's Shroud - Part III
ags:thedevilsshroudpart4       The Devil's Shroud - Part IV
ags:thedigitalspell            The Digital Spell
ags:thedisgracedprince         The disgraced prince
ags:thedollhousech1            The Dollhouse - Chapter 1: Plaything
ags:thedome                    The Dome
ags:thedreamjobep1             The Dream Job, ep. 1
ags:thedusseldorfconspiracy    Jessica Plunkenstein and the Düsseldorf Conspiracy
ags:thedwarvendaggerofblitz    The Dwarven Dagger of Blitz
ags:thedwarvendaggerofblitzch2 The Dwarven Dagger of Blitz - Chapter 2
ags:theelevator                The Elevator
ags:theendlessnight            The Endless Night
ags:theenergizer               The Energizer
ags:theepicadventures          The epic adventures of Barry
ags:theeternalnight            The Eternal Night
ags:theeverbeginningtale       The Ever-Beginning Tale
ags:theexecutionofanneboleyn   The Execution of Anne Boleyn
ags:theexperimentp1            The Experiment - Part 1: The Laboratory
ags:theexperimentp2            The Experiment - Part 2: Menacing Darkness
ags:thefaketrix                The Faketrix
ags:thefamilytreasure          The Family Treasure
ags:thefarmep1                 The Farm - Episode One
ags:thefarmmags                The Farm
ags:theficklehandsoffate       The Fickle Hands of Fate
ags:thefind                    The Find
ags:thefront                   The Front
ags:thefrozenshore             The Frozen Shore
ags:thefurtheststation         The Furthest Station
ags:thegardenofhades           The Garden of Hades
ags:theglasssplinters          The Glass Splinters
ags:thegourmet                 The Gourmet
ags:thegreatcasserolecaper     The Great Casserole Caper
ags:thegreatstrokeoff          The Great Stroke-Off!
ags:thegreenroom               The Greenroom - An Escape Room Adventure
ags:thegruglegends             The Grug Legends
ags:theguilteternal            The Guilt Eternal
ags:thehamlet                  The Hamlet
ags:thehat                     The Hat
ags:thehauntedhouse            The Haunted House
ags:theheist                   The Heist
ags:thehobbitriseofthedragonking The Hobbit: Rise of the Dragon King
ags:thehousethatatemysoul      The house that ate my soul
ags:thehousewithoutwindows     The House Without Windows
ags:thehuntforgoldbeard        The hunt for Goldbeard
ags:thehuntforshaunbinda       The hunt for Shaun Binda
ags:theinfinitystring          The Infinity String
ags:theiraqiparadox            The Iraqi Paradox
ags:thejackyard                The Jackyard
ags:thejimihendrixcase         The Jimi Hendrix Case
ags:thejourneyhomep1           The Journey Home - Part One
ags:thejourneyofiesir          The Journey of Iesir
ags:thelastharvest             The Last Harvest
ags:thelastsupperawhodunnit    The Last Supper, A Whodunnit
ags:thelighthouse              The Lighthouse
ags:thelightningspell          The Lightning Spell
ags:theloneloser               The Lone Loser
ags:theloneplanet              The Lone Planet
ags:thelongtrip                The Long Trip
ags:thelurkinghorror           The Lurking Horror
ags:themajesticconspiracy      The Majestic Conspiracy
ags:themaninthehat             The Man in the Hat
ags:themanisee                 The Man That Only I Can See
ags:themarionette              The Marionette
ags:themccarthychroniclesep1   The McCarthy Chronicles - Episode 1
ags:themcreedcase              The McReed Case
ags:themind                    The Mind
ags:themuseum                  The Museum
ags:themysteriesofstiegomoor1  The Mysteries of Stiego Moor - Volume One: The Wicker Man
ags:themysteryofhauntedhollow  The Mystery of Haunted Hollow
ags:thenetherworld             The Netherworld
ags:thenextcurse               The Next Curse
ags:thenorthcrown              The North Crown
ags:theoccultist               The Occultist - Old Growth
ags:theoffice                  The Office
ags:theoracle                  The Oracle
ags:theoscillation             The Oscillation
ags:theoven                    The Oven
ags:thepaparazziprince         The Paparazzi Prince; and the Quest for Headlines
ags:thepark                    The Park
ags:theparrotsnatchers         The Parrot Snatchers
ags:thepathpumpkin             The Path of the Pumpkin
ags:thepenthouse               The Penthouse
ags:theperfectmurder           The Perfect Murder
ags:thephantominheritance      The Phantom Inheritance
ags:thequestfortheholysalsa    The Quest for the Holy Salsa
ags:thequesttozooloo           The Quest To Zooloo
ags:therail                    The Rail
ags:theratpack                 The Rat Pack
ags:there                      There
ags:thereaper                  The Reaper
ags:therebirth                 The Rebirth
ags:therent                    The Rent / L'Affitto
ags:theroadtomurder            Laura Bow in The Road to Murder
ags:therobolovers              The Robolovers
ags:therotaryclub              The Rotary Club
ags:theschool                  The School
ags:thesearch                  The Search
ags:thesecretofchunkysalsa     The Secret of Chunky Salsa
ags:thesecretofgoldenriver     Fynewrylst Memories: The Secret of Golden River
ags:thesecretofhuttongrammarschool The Secret of Hutton Church of England Grammar School
ags:thesecretofmaikeisland     The Secret of Maike Island
ags:thesecretofmountmonkey     The Secret of Mount Monkey
ags:thesecretplanch1           The Secret Plan - Chapter 1: Running to stand still
ags:theshadowavenger           The Shadow Avenger: It's personal!
ags:theshaft                   The Shaft
ags:theshortestjourney         The Shortest Journey
ags:thesmallestpoints          The Smallest Points
ags:thesnaplock                The Snaplock
ags:thespiderweb               The Spider's Web
ags:thespoons                  The Spoons
ags:thestarryskyaboveme        The Starry Sky Above Me
ags:thesummoned                The Summoned
ags:thesundownmystery          The Sundown mystery
ags:thesurvivors               The Survivors / Les Survivants
ags:thesylph                   The Colorless Sylph
ags:thethickening              Reality-on-the-Norm 13:13^2 The Thickening
ags:thetombofthemoon           The Tomb of the Moon
ags:thetrap                    The Trap - A Darcy Muldoon Adventure
ags:thetreasuredmedallion      The Treasured Medallion
ags:thetreasureoflochinch      The Treasure of Loch Inch
ags:theuncertaintymachine      The Uncertainty Machine
ags:theunicated                The Unicated
ags:theupliftmofopartyplan     MI5 Bob: The Uplift Mofo Party Plan
ags:thevacuum                  The Vacuum
ags:thevillage                 The Village
ags:thevisitor1                The Visitor
ags:thevisitor2                The Visitor 2
ags:thevisitor3                The Visitor 3
ags:thevoid                    The Void
ags:thewhitecanvas             The White Canvas / Lienzo en Blanco
ags:thewife                    The wife who wasn't there
ags:thewill                    The Will
ags:theworm                    The Worm
ags:thinker                    Thinker
ags:thiscitynight              This City at Night
ags:thisgame                   This Game
ags:thisoddfeeling             This Odd Feeling
ags:thistall                   You must be this tall
ags:thisway                    This is the Way
ags:threeguyswalkintoheaven    Three Guys Walk Into Heaven
ags:threepwoodnightmare        Threepwood's Nightmare
ags:throwme                    Throw Me in the River
ags:thrymly                    Thrymly Disguised
ags:tigerhawk                  Tiger Hawk Squadron
ags:tilepuzzle                 Tile Puzzle
ags:tillcows                   'Til Cows Tear us Apart
ags:tiltor                     TiLTOR
ags:timeparadox                TIME-PARADOX 2009
ags:timequest1                 Time Quest
ags:timequest2                 Time Quest 2
ags:timesinkofchronos          Timesink of Chronos
ags:timestone                  Time Stone
ags:timetrial                  Time Trial
ags:timothylande               Timothy Lande
ags:tinysoccer                 Tiny Soccer Manager Stories
ags:tirnanog                   Tir Na Nog
ags:toffeetrouble              Toffee Trouble in Creamville
ags:tomandjimi                 Tom and Jimi in Blowout!
ags:tomateundescanso           Tómate un Descanso
ags:tombhunter                 Tomb Hunter: Ramitupem
ags:tomhanksaway               Tom Hanks Away: Wilson's Revenge
ags:tooblivion                 Who sent me to Oblivion
ags:toomanykittens             Too Many Kittens
ags:topus                      You rock, Topus!
ags:totheend                   To the end of the way
ags:tothemom                   To The Mountains Of Madness
ags:tots                       T.O.T.S. : Trick-Or-Treat Simulator
ags:totti1                     Totti's missing claw
ags:totti2                     Good Evening Totti
ags:tradeforward               Trade it forward
ags:trancepacific              Trance-Pacific
ags:trappedinabuilding         Trapped in a building
ags:trashquest                 Trash Quest
ags:travelers                  TRAVELERS
ags:trevordaisoninouterspace   Trevor Daison in outer space - Chapter One: Trouble on Percicron IV
ags:trexmusclesam1             T-Rex and Muscle Sam: Big Trouble in Smashing Potatoes Federation
ags:trexmusclesam2             T-Rex and Muscle Sam: A New Kickstart!
ags:trianglehead               Triangle Head's Adventure
ags:trickers                   Trickers
ags:trilbysnotes               Trilby's Notes
ags:trilbytheartoftheft        Trilby: The Art Of Theft
ags:trivialpassyouit           Trivial Pass You It
ags:trollsong                  Troll Song - Verse One: Completely Stoned
ags:tropicjim                  Tropic Jim's Sweet Island Adventure
ags:troublecorner              Trouble on the Corner of Sugar & Spice
ags:troublekingdom             Trouble Kingdom
ags:troublingteleportation     Troubling Teleportation
ags:trumpsbed                  Shit in Trump's Bed
ags:truthmatter                The Truth of the Matter
ags:tsomi2                     The Secret of Monkey Island 2
ags:turtlesintime              Turtles Ninja in Time
ags:tvabroder                  Two Brothers / Två bröder
ags:tvquest2015                Tv Quest
ags:twelvethirteense           Twelve Thirteen - Special Edition
ags:twelvethirteenep1          Twelve Thirteen - Episode 1
ags:twelvethirteenep2          Twelve Thirteen - Episode 2
ags:twelvethirteenep3          Twelve Thirteen - Episode 3
ags:twentiesflappersvsthemummy Twenties Flappers vs. The Mummy
ags:twoofakind                 Two of a Kind
ags:ugalembrace                Ugal's Embrace
ags:uglyfiles                  The Ugly Files
ags:ulitsadimitrova            Ulitsa Dimitrova
ags:unbound                    Unbound
ags:uncontrollable             UNCONTROLLABLE
ags:underwateradv              Underwater Adventures
ags:underworld                 The Underworld
ags:unexpectedguest            Unexpected Guest
ags:unexpectedquest            Unexpected Quest
ags:unfinished                 Unfinished
ags:unfinishedbusiness         Unfinished Business
ags:unfinishedtales            Unfinished Tales / Cuentos Inconclusos
ags:unfoldingspider            The Unfolding Spider
ags:unganeedsmumba             UNGA needs MUMBA
ags:unintelligentdesign        Unintelligent Design
ags:unlicensedkill             Unlicensed to Kill
ags:unprintablemagenta         The unprintable Magenta
ags:unprofe                    Un Profe
ags:unraveling                 The Tapestry - Chapter 1: The Unraveling
ags:unscripted                 Unscripted
ags:unsolvedmystery            Bob Smith and the Unsolved Case of Mystery
ags:untildawn                  Until Dawn Tomorrow
ags:untilfurthernotice         Stories of the unexpected: 'Until further notice'
ags:updatequest                Update Quest
ags:upducted                   Upducted
ags:urbanwitchstory            Urban Witch Story
ags:uydearmyfriendsremake      Urusei Yatsura: Dear My Friends Remake
ags:urgentquest                Urgent Quest
ags:uropa                      U-ropa
ags:utopiaoftyrant             Utopia of Tyrant
ags:vacantbodies               Vacant Bodies
ags:vacationquestthing         Vacation Quest... Thing
ags:valhallaextinction         Valhalla Extinction
ags:valis                      Valis
ags:vankairbreak               van K. Airbreak
ags:vectorvendetta             Vector Vendetta
ags:vegetablepatch             Vegetable Patch Extreem Turbo
ags:vegetablepatch2            Vegetable Patch Extreem Turbo 2
ags:veggietales3d              Veggie Tales 3D
ags:venator                    Venator
ags:vertigo                    Vertigo
ags:verybadtaste               Very Bad Taste: Dels don't hide!
ags:veteranshootout            Veteran shootout
ags:vexationisland             Vexation Island - The Game
ags:vicwreckleshalloweencostume Vic Wreckle's Halloween Costume
ags:vikingguardsman            The Viking Guardsman
ags:virmachina                 VIRMACHINA
ags:virtualpiano               Virtual Piano
ags:vivarium                   Vivarium
ags:voyagesfuturo              Les Voyages de Futuro
ags:vohaulsrevenge2            Space Quest XII: Vohaul's Revenge II
ags:voodoodave                 Voodoo Dave and the Tablecloth Mystery
ags:vrrontour                  VR Reality-on-the-Norm Tour 
ags:wagesofdarkness            The Wages of Darkness
ags:walkcyclegen               SSH's Walkcycle Generator
ags:wallardgromoid             Wallard & Gromoid in: A Planned Day Out
ags:walle                      WALL-E Fan Adventure
ags:wallyweasel                The Wacky World of Wally Weasel
ags:waltersasteroid            Walter's Asteroid
ags:warningfragilech1          Warning: Fragile! - Chapter I: Operation Blindhawk
ags:warptile                   WarpTile
ags:warstars                   War Stars
ags:washedashore               Washed Ashore
ags:wasted                     Wasted
ags:waterquest                 Water Quest
ags:wduprodigal                World of Darkness Unbound - Prodigal
ags:wearevectors               We Are Vectors
ags:weathered                  Weathered
ags:wegotlost                  I Think We Got Lost
ags:weightloss                 Narcoleptic Weight Loss Expert
ags:welcometodarklake          Welcome to Dark Lake
ags:wellmeetagain              We'll meet again...
ags:wellwellwell               Well, well, well, what have we here?
ags:wendywhedon1               Wendy Whedon chapitre 1 : Le Ranch Mortensen
ags:wendywhedon2               Wendy Whedon chapitre 2 : Les Rejets de la Nature
ags:wendywhedon3               Wendy Whedon chapitre 3 : Le Kasshinkston Express
ags:westroot                   West of the Root
ags:wet                        Wet
ags:whathappened               What the F--K happened!?
ags:whatisthat                 What is that
ags:whatlinusbruckmansees      What Linus Bruckman Sees When His Eyes Are Closed
ags:whattimeisit               Artie Salomon: What time is it?
ags:wheeloftorture             Wheel of Torture
ags:whentheworldcalls          When the world calls...
ags:whentimestops              Reef Rivers in: When Time Stops
ags:wherebedragons             Where Be Dragons?
ags:wheredidhumansgo           Where Did the Humans Go?
ags:wheredidsamgo              Where did Sam go?
ags:wheresmhatma               Where's M' Hat Ma?
ags:whichwitch                 Which Witch
ags:whiskeyweather             Whiskey Weather
ags:whitemoredeadep1           White is more DEAD - Episode I
ags:whitemoredeadep2           White is more DEAD - Episode II
ags:whitemoredeadep3           White is more DEAD - Episode III
ags:whokilledbambi             Who Killed Bambi?
ags:whopper                    What a whopper!
ags:whowantstoliveagain        James Bond - Who wants to live again?
ags:whowantstoliveforever      Who wants to live forever?
ags:wickedwitchwest            The Wicked Witch of the West
ags:wilfred2088                Wilfred: 2088
ags:williamsnightmare          Williams Nightmare
ags:willowhouse                Willow House
ags:winamillion                Win a Million!
ags:winnersdontdodrugs         Winners Don't Do Drugs
ags:winterrose                 The Winter Rose
ags:wisp                       Wisp
ags:witchlullaby               The Witch's Lullaby
ags:witchnight                 Witch Night
ags:witchron                   Witch!
ags:witchwizardcup             The Witch, the Wizard and the Blue Cup
ags:witchywoo                  Witchy Woo
ags:withoutaprayer             Without a Prayer
ags:witness                    Witness!
ags:wizardhangover             Wizard Hangover ExtreamZz!
ags:wizardhood                 Wizardhood
ags:wolfcountry                Wolf Country
ags:woo                        WOO: World of Our Own
ags:woolyrockbottom            Wooly Rockbottom and the Quest for the Golden Beard of Thor!
ags:worldisweird               The World is Weird
ags:worldofwarcraftquest       World of Warcraft: The IMBA Quest
ags:wormholech1                Wormhole - Capítulo 1
ags:wrathofthesolonoids        Doctor Who: Wrath of the Solonoids
ags:wrecked                    Wrecked
ags:wretcher                   Wretcher
ags:writersblocks              Writer's Blocks
ags:wrongchannel               Wrong Channel
ags:wulffenstein               Wulffenstein – Im Kreuzfeuer der Reporter
ags:y                          Y
ags:yago                       Yago, the Coquerrestrial / Yago, el Coquerrestre
ags:yoda                       Yoda
ags:yourgrace                  Your Grace
ags:yourlate                   9 Minutes! Your late!
ags:zak2                       The New Adventures of Zak McKracken
ags:zakrepixeled               Zak McKracken and the Alien Mindbenders - repixeled
ags:zakseamonster              Zak McKracken and the Lonely Sea Monster
ags:zeke                       Zeke and the Island of Barentsev
ags:zippermeteor               The Zipper Meteor
ags:zogmoonbuckle              Zog Moonbuckle: The Mysterious Planet
ags:zombieattack               Zombie Attack
ags:zombiefish                 Night of the Zombie Fish!
ags:zooreal                    ZooReal
ags:zugzwang                   Zugzwang
ags:evildead4                  Evil Dead 4
ags:goodman                    Good Man
ags:tbdiy                      The BAD day in year
ags:einsteinmachine            Einstein Machine
ags:prisonersofice             Prisoners of Ice
ags:snowyadventures            Snowy Adventures
asylum:asylum                  Sanitarium
avalanche:avalanche            Lord Avalot d'Argent
bbvs:bbvs                      Beavis and Butt-head in Virtual Stupidity
bladerunner:bladerunner        Blade Runner
bladerunner:bladerunner-final  Blade Runner with restored content
bladerunner:bladerunner-ee     Blade Runner: Enhanced Edition
buried:buried                  The Journeyman Project 2: Buried in Time
cge:soltys                     Soltys
cge2:sfinx                     Sfinx
chewy:chewy                    Chewy: Esc from F5
cine:fw                        Future Wars
cine:os                        Operation Stealth
composer:babayaga              Magic Tales: Baba Yaga and the Magic Geese
composer:darby                 Darby the Dragon
composer:gregory               Gregory and the Hot Air Balloon
composer:imoking               Magic Tales: Imo and the King
composer:liam                  Magic Tales: Liam Finds a Story
composer:littlesamurai         Magic Tales: The Little Samurai
composer:magictales            Magic Tales
composer:princess              Magic Tales: The Princess and the Crab
composer:sleepingcub           Magic Tales: Sleeping Cub's Test of Courage
cruise:cruise                  Cruise for a Corpse
cryo:losteden                  Lost Eden
cryomni3d:atlantis             Atlantis: The Lost Tales
cryomni3d:versailles           Versailles 1685
director:director              Macromedia Director Game
director:directortest          Macromedia Director Test Target
director:directortest-all      Macromedia Director All Movies Test Target
director:directorshokai        Macromedia Director紹介
director:theapartment          The Apartment, Interactive demo
director:dirmacromedia         Macromedia Director
director:dirmacromind          MacroMind Director
director:lingoexpo             Director 4 Lingo Expo and Sample Titles
director:10plus2               10+2
director:1stcdtoddler          My First CD-ROM: Toddler School
director:3bessones             Les Tres Bessones: Jugar i Aprendre
director:abclunch              My Alphabet Lunch
director:abcpacovska           Alphabet: Play with the ABCs
director:abcpalsafety          Safety Scavenger Hunt
director:abductthis            Abduct This!
director:afiles                The A-Files
director:agapito               Agapito's Crazy Adventure
director:alice                 Alice: An Interactive Museum
director:alphabet              The Interactive Alphabet
director:amandastories         AmandaStories
director:amber                 AMBER: Journeys Beyond
director:amertailmb            An American Tail Interactive MovieBook
director:arcade                Classic Arcade
director:arcadeairattack       Classic Arcade Air Attack
director:arcadeboing           Classic Arcade Boing
director:arcadehockey          Classic Arcade Air Hockey
director:arcadelander          Classic Arcade Lander
director:arcadesubs            Classic Arcade Subs
director:arcofdoom             Arc of Doom
director:artofmagic            Learn the Art of Magic with Jay Alexander
director:artrageous            ArtRageous!
director:artus1                Artus against the Demon of the Museum
director:atvrally              ATV Rally
director:babarcoins            Babar and the Royal Coin Caper
director:babesintoyland        Babes in Toyland: An Interactive Adventure
director:backpackerjr          BackPacker Junior
director:badday                Bad Day on the Midway
director:badmilk               Bad Milk
director:bananasfun            Bananas in Pyjamas: It's Fun Time
director:bananaspack           Bananas in Pyjamas: Fun Pack
director:bananasparty          Bananas in Pyjamas: It's Party Time
director:barbnail              Barbie Nail Designer
director:barbpauper            Barbie as the Princess and the Pauper
director:barbrapunzel          Barbie as Rapunzel: A Creative Adventure
director:barbswanlake          Barbie of Swan Lake: The Enchanted Forest
director:basilbaker            Venice Under Glass: A Basil Baker Mystery Adventure
director:bbbighelpers          Little Bears Make Big Helpers: Life's Little Lessons with the Berenstain Bears
director:bearfamily            A Bear Family Adventure
director:beautyorbeast         Beauty or the Beast
director:betterd               The Better Dead Ratification
director:beyondthewall         Beyond the Wall of Stars
director:biblechamps           Bible Champions: The Birth of Jesus
director:birdlife              Shelley Duvall's It's a Bird's Life
director:blinddate             National Lampoon's Blind Date
director:blinkybill1           Blinky Bill's Ghost Cave
director:blinkyk1              Blinky Bill: Play and Learn - Kindergarten
director:blinkyps              Blinky Bill: Play and Learn - Preschool
director:blinkyy1              Blinky Bill: Play and Learn - Year 1
director:bobcastle             Bob the Builder: Bob's Castle Adventure
director:bodypark              Body Park
director:brer                  Brer Rabbit and the Wonderful Tar Baby
director:buzz1                 Buzz Lightyear 1st Grade
director:casino                Casino!
director:casino5p              Casino 5 Pack
director:casinoblackjack       Casino Black Jack
director:casinokeno            Casino Keno
director:casinopoker           Casino Poker
director:casinoslots           Casino Slots
director:casperact             Casper Activity Center
director:cassandra             The Cassandra Galleries
director:catcameback           The Cat Came Back
director:catshats              Black Cats and Pointed Hats
director:cbible                Children's Bible Stories
director:cclown                A Color Clown Comes to Town
director:ceremony              Ceremony of Innocence
director:chaos                 The C.H.A.O.S. Continuum
director:checkersvillage       Checkers' Village
director:chopsuey              Chop Suey
director:circus                Circus!
director:connections           Connections
director:cracking              Cracking the Conspiracy
director:criticalpath          Critical Path
director:crusader              Crusader: A Conspiracy in the Kingdom of Jerusalem
director:crusader2000          Crusader: Edition 2000
director:crystalskull          The Crystal Skull
director:daedalus              The Daedalus Encounter
director:darkeye               The Dark Eye
director:dazzeloids            Dazzeloids
director:dcanyon               Devil's Canyon: A Dinamation Adventure
director:deathstar             Death Star Destructo
director:derratsorcerum        Derrat Sorcerum
director:devo                  DEVO Presents: Adventures of the Smart Patrol
director:digby                 Digby's Adventures: Tales of a 1-Pound Dog
director:dimensionq            Iz and Auggie: Escape from Dimension Q
director:dispix2and3           Disney Pixar Learning: 2nd & 3rd Grade
director:donnamatrix           Donna Matrix
director:draculassecret        Dracula's Secret
director:easternmind           Eastern Mind: The Lost Souls of Tong Nou
director:eddieminx             Eddie & Minx: Waking Up the Magic
director:elmopreschool         Elmo's Preschool
director:elroybug              Elroy Goes Bugzerk
director:elroycostume          Elroy's Costume Closet
director:elroypave             Elroy Hits the Pavement
director:erdisaster            Emergency Room: Disaster Strikes
director:exploder              Winblows Exploder
director:fct                   Big Top's Cartoon Toolbox Starring Felix the Cat
director:fctexport             Felix's Cartoon Transformer
director:fctplayer             Felix Cartoon Player
director:fff                   Four Footed Friends
director:fishwish              The Fish Who Could Wish
director:flipper               Flipper
director:flipper1              The Three Worlds of Flipper & Lopaka
director:flipper2              Flipper & Lopaka: Secrets of the Deep
director:foocastle             Foo Castle
director:forestia              Forestia: The Great Adventure
director:fpbacon               Fisher-Price Big Action Construction
director:fpbagarage            Fisher-Price Big Action Garage
director:fpdollhouse           Fisher-Price Time to Play: Grand Dollhouse
director:fpgacastle2           Great Adventures by Fisher-Price: Castle (1998)
director:fpgapirates           Great Adventures by Fisher-Price: Pirates
director:fpgawestern           Great Adventures by Fisher-Price: Wild Western Town
director:fplit                 Fisher-Price Learning in Toyland
director:fplpairport           Fisher-Price Little People: Discovery Airport
director:fplpxmas              Fisher-Price Little People: Christmas Activity Center
director:fpready1              Fisher-Price Ready for School: First Grade
director:fpreadyk              Fisher-Price Ready for School: Kindergarten
director:fpreadyp              Fisher-Price Ready for Preschool
director:fpreadyt              Fisher-Price Ready for School: Toddler
director:fprpbaxter            Fisher-Price Read & Play: Baxter's Birthday
director:fprpyolanda           Fisher-Price Read & Play: Yolanda Yellsalot
director:frankac               Franklin's Activity Center
director:frankenstein          Frankenstein: Through the Eyes of the Monster
director:franklm               Franklin Learns Math
director:frankrw               Franklin's Reading World
director:freakshow             Freak Show
director:fsky                  A Field Trip to the Sky
director:fuzzyfloppy1          Fuzzy & Floppy: The Adventure of the Golden Bee
director:gadget                Gadget: Invention, Travel & Adventure
director:gadgetpaf             Gadget: Past as Future
director:garage                Garage: Bad Dream Adventure
director:garfieldmadcats       Garfield: Mad about Cats
director:garygadget1           Building Cars with Gary Gadget
director:generations           Generations
director:getaheadmath          Math Heads
director:getaheadmathcr        Math Heads Creator
director:getaheadstrat         Strategy Heads
director:getaheadstratcr       Strategy Heads Creator
director:ggmd                  The Great Green Mouse Disaster
director:ggmdmaze              The Great Green Mouse Disaster: Mouse Maze
director:ggmdpics              The Great Green Mouse Disaster: Gallery
director:ggmdsuper             The Great Green Mouse Disaster: Super Game
director:gigglecity            Infinity City
director:gigglefarm            AlphaBonk Farm
director:giggletour            The Gigglebone Gang World Tour
director:gigglevania           Pantsylvania: The Kingdom of the Fancy Pants
director:goferwinkel           Goferwinkel's Adventures: The Lavender Land
director:goldilocks            Goldilocks Gamebook
director:gordak                Gord@k
director:grammarplaytime2      Grammar Playtime Vol.2: Asking Questions
director:gundam0079            Gundam 0079: The War for Earth
director:guscarn               Gus Goes to the Kooky Carnival
director:gusolis               Gus Goes to Cyberopolis
director:guspark               Gus Goes to CyberStone Park
director:gussshc               Gus and the CyberBuds Software SchoolHouse Collection
director:gustown               Gus Goes to Cybertown
director:hamletmurder          Hamlet: A Murder Mystery
director:hamsterland1          Busy People of Hamsterland
director:hamsterland2          Hamsterland: The Time Machine
director:heidi                 Heidi: Your World is the Mountains
director:hellcab               Hell Cab
director:hhouse                Gahan Wilson's The Ultimate Haunted House
director:hkbigfun              Hello Kitty Big Fun Deluxe
director:horrortour1           Zeddas: Servant of Sheol
director:hotwheelscamaro       Hot Wheels Computer Cars - '93 Camaro
director:hotwheelshydro        Hot Wheels Computer Cars - Hydroplane
director:hotwheelsmustang      Hot Wheels Computer Cars - 1996 Mustang GT
director:hotwheelspistons      Hot Wheels Computer Cars - Power Pistons
director:hotwheelsrigor        Hot Wheels Computer Cars - Rigor Motor
director:hotwheelswiener       Hot Wheels Computer Cars - Oscar Mayer Wienermobile
director:id4p1                 iD4 Mission Disk 1 - Alien Supreme Commander
director:id4p2                 iD4 Mission Disk 2 - Alien Science Officer
director:id4p3                 iD4 Mission Disk 3 - Warrior Alien
director:id4p4                 iD4 Mission Disk 4 - Alien Navigator
director:id4p5                 iD4 Mission Disk 5 - Captain Steve Hiller
director:id4p6                 iD4 Mission Disk 6 - Dave's Computer
director:id4p7                 iD4 Mission Disk 7 - President Whitmore
director:id4p8                 iD4 Mission Disk 8 - Alien Attack Fighter
director:id4p9                 iD4 Mission Disk 9 - FA-18 Fighter Jet
director:id4p10                iD4 Mission Disk 10 - Alien Bomber
director:id4p11                iD4 Mission Disk 11 - Area 51
director:improv                Don't Quit Your Day Job
director:ingenious             Ingenious!
director:ingenioused           Ingenious! Education Resources
director:ironhelix             Iron Helix
director:isaslm                I Saw A Strange Little Man
director:isis                  Isis
director:ispy                  I Spy
director:ispyschool            I Spy School Days
director:ispyspooky            I Spy Spooky Mansion
director:jewels1               Jewels of the Oracle
director:jewels2               Gems of Darkness
director:jman                  The Journeyman Project
director:jman2                 The Journeyman Project 2: Buried in Time
director:jmmd                  Just Me & My Dad
director:js123                 JumpStart Numbers
director:jsabc                 JumpStart ABC's
director:jsmusic               JumpStart Music
director:jsspanish             JumpStart Spanish
director:jsworld1              JumpStart World: First Grade
director:jsworld1t             JumpStart World: Teacher Control Panel 1st Grade
director:jsworld2              JumpStart World: Second Grade
director:jsworld2t             JumpStart World: Teacher Control Panel 2nd Grade
director:jsworldk              JumpStart World: Kindergarten
director:jsworldp              JumpStart World: Preschool
director:jumpaheadss2000at     Jump Ahead Starting School 2000: Assessment Test
director:jumpaheadss2000wb     Jump Ahead Starting School 2000: Workbook
director:karma                 Karma: Curse of the 12 Caves
director:kellyparade           Kelly Club Pet Parade
director:keroppi               Keroppi Day Hopper
director:kidsmathsquest        Kid's Maths Quest
director:kingandi              The King and I: Animated Thinking Adventure
director:korkydragons          Dragons
director:kothhoot              King of the Hill: Hootenany
director:koththunt             King of the Hill: Texas Hunting
director:kyoto                 Cosmology of Kyoto
director:lbkinder              Maurice Sendak's Little Bear Kindergarten Thinking Adventures
director:lbpre                 Maurice Sendak's Little Bear Preschool Thinking Adventures
director:lbtpreschool          The Land Before Time: Preschool Adventure
director:legendsofoz           The Legends of Oz
director:letters               Letters
director:louiscatorze          Louis Cat Orze: The Mystery of the Queen's Necklace
director:luxor                 Secrets of the Luxor
director:madcc12               Madeline Classroom Companion: 1st & 2nd Grade
director:madccpk               Madeline Classroom Companion: Preschool & Kindergarten
director:madpup                Madeline and the Magnificent Puppet Show: A Learning Journey
director:madtg                 Madeline Thinking Games
director:majestic              Majestic Part I: Alien Encounter
director:maniacsports          Maniac Sports
director:martian               Ray Bradbury's The Martian Chronicles Adventure Game
director:mask                  The Mask: The Origin
director:mastermansion         Masterpiece Mansion
director:mastermansionex       Masterpiece Mansion: Art Explorer
director:mathacejr             Math Ace Jr.
director:mathmystery           Math Blaster Mystery: The Great Brain Robbery
director:maze                  The Riddle of the Maze
director:mckenzie              McKenzie & Co.
director:mckenziemf            McKenzie & Co.: More Friends
director:mcluhan               Understanding McLuhan
director:mcmillennium          Mission Code: Millennium
director:mediaband             Meet MediaBand
director:meetchuck             Meet Chuck
director:melements             Masters of the Elements
director:mentalmaths           Mental Maths Booster
director:miamath               Mia's Math Adventure: Just in Time!
director:miareading1           Mia's Reading Adventure: The Search for Grandma's Remedy
director:mickeyk               Mickey Mouse Kindergarten
director:mickeyp               Mickey Mouse Preschool
director:mickeyt               Mickey Mouse Toddler
director:microshaft            Microshaft Winblows
director:mightymachines        Mighty Machines
director:milo                  Milo
director:milomagical           Milo and the Magical Stones
director:mirage                Mirage
director:missionplanetx        Mission To Planet X: Internet Coach for Kids
director:mmalgebra             Multimedia Algebra
director:mmiqtest              Multimedia IQ Test
director:mmmath3               Mission Masters Math Grade 3: Defeat Dirty D!
director:mrsquack              Reading with Peter Cottontail: The Story of Mrs. Quack
director:mummy                 Mummy: Tomb of the Pharaoh
director:muppetkidsearly5      Muppets Kids Early Learning Series Volume 5: Sound Patterns: Phonics
director:muppetkidsthinking    Muppets Kids Thinking Skills
director:murderbrett           Who Killed Brett Penance?
director:murdermagic           The Magic Death
director:murdersam             Who Killed Sam Rupert?
director:murdertaylor          Who Killed Taylor French? The Case of the Undressed Reporter
director:myfavmonster          My Favourite Monster
director:myfirstwords          My First Reading & Spelling Words
director:mylk                  Mylk
director:necrobius             Necrobius
director:necromancer           Necromancer
director:nightcafe             Night Café
director:nikolaiknights        Nikolai in Time: In the Time of the Knights
director:nikolaimystery        Nikolai's Mysteries: The Mystery of the Black Windows
director:nikolaipirates        Nikolai's Pirates
director:nikolaispace          Nikolai in Outer Space
director:nikolaispaceedu       Nikolai Space Education
director:nikolaitoys           NN'nN Toy Makers
director:nikolaitreats         Nikolai's Treats
director:nile                  Nile: Passage to Egypt
director:nine                  9: The Last Resort
director:noddyfair             Noddy and the Toyland Fair
director:noddyschool           Noddy: Let's Get Ready For School
director:noddytoytown          Noddy: The Magic of ToyTown on a CD-ROM
director:noir                  Noir: A Shadowy Thriller
director:nurseryrhymes         Multimedia Nursery Rhymes
director:okay2000              O!Kay! Best of 2000
director:okaydemo              O!Kay! Probier' mal! Try out!
director:okaydownunder         O!Kay! Down Under
director:okaydragon            O!Kay! Red Dragon
director:okayfriends           O!Kay! Friends
director:okayhenry             O!Kay! Henry in Love
director:okaytruehero          O!Kay! A True Hero
director:operafatal            Opera Fatal
director:oslotg                Adventures with Oslo: Tools and Gadgets
director:oztma                 Oz: The Magical Adventure
director:paparazzi             Paparazzi!: Tales of Tinseltown
director:paws                  P.A.W.S.: Personal Automated Wagging System
director:pbbear                P. B. Bear's Birthday Party
director:pecosbill             Pecos Bill
director:perdido               Lost in the Amazon
director:peterrabbit           The Adventures of Peter Rabbit and Benjamin Bunny
director:pennyhorse            Penny Horse
director:physicus              Physicus: Save the World with Science!
director:phonicsquest          Disney Phonics Quest
director:physicus              Physicus: Save the World with Science!
director:pingu1                Pingu: A Barrel of Fun!
director:pingu2                Pingu and Friends
director:pippi                 Astrid Lindgren's Pippi
director:planetarizona         Escape from Planet Arizona
director:playroom              The Playroom
director:poohac                Winnie the Pooh Activity Center
director:poohb                 Winnie the Pooh Baby
director:poohk                 Winnie the Pooh Kindergarten
director:poohp                 Winnie the Pooh Preschool
director:pooht                 Winnie the Pooh Toddler
director:princessfashion       Disney's Princess Fashion Boutique
director:pyst                  Pyst
director:pyst2                 Driven: The Sequel to Pyst
director:pystmake              The Making of Pyst
director:quantumgate2          The Vortex: Quantum Gate II
director:rainbowfish1          Rainbow Fish: The most beautiful fish in the ocean!
director:rainbowfish2          Rainbow Fish and the Whale
director:realpool              RealPool
director:rhem1                 Rhem
director:rhlava                Rescue Heroes: Lava Landslide
director:rhmeteor              Rescue Heroes: Meteor Madness
director:rodneyfs              Rodney's Funscreen
director:rodneyfs2             Rodney's Funscreen² Extreme: Dinky's Revenge
director:rodneyww              Rodney's Wonder Window
director:safecracker           Safecracker
director:sajaklucky            Pat Sajak's Lucky Letters
director:screamingmetal        Screaming Metal
director:searchlearn           Search & Learn Adventures
director:secretkeys            Search for the Secret Keys with Mickey
director:secretpaths1          Secret Paths in the Forest
director:sfpd                  SFPD Homicide Case File: The Body in the Bay
director:shellwhirl            Shell Whirl
director:shr1st2nd             Schoolhouse Rock!: 1st & 2nd Grade Essentials
director:shr3rd4th             Schoolhouse Rock!: 3rd & 4th Grade Essentials
director:shramerica            Schoolhouse Rock!: America Rock
director:shrgrammar            Schoolhouse Rock!: Grammar Rock
director:shrlucky              Schoolhouse Rock!: Lucky's Math Arcade
director:shrmath               Schoolhouse Rock!: Math Rock
director:shrmess               Schoolhouse Rock!: 1st-4th Grade Math Essentials
director:simpsonsplayer        The Simpsons Cartoon Player
director:simpsonsstudio        The Simpsons Cartoon Studio
director:sitfarm               Sitting on the Farm
director:skeeto10              Skipper & Skeeto: Fun in the Park
director:skippy                Skippy and the Curse of the Temple of Ock
director:skyborg               SkyBorg: Into the Vortex
director:slamdunktyping        Slam Dunk Typing
director:smallfish             Small Fish
director:smartsteps3rd         Smart Steps 3rd Grade
director:snh                   A Silly Noisy House
director:snow7han              Snow White and the Seven Hansels: The Fairy Tale Game
director:spacestationalpha     Space Station Alpha: The Encounter
director:spellingbee           Arc Media Spelling Bee
director:spyclub               Spy Club
director:spykids3d             Spy Kids 3-D: Game Over
director:starwarped            Star Warped
director:staytooned            Stay Tooned!
director:superspy              SuperSpy 1
director:supertutorgram        Super Tutor Grammar
director:takeru                Buichi Terasawa's Takeru: Letter of the Law
director:teamxtreme1           Operation: Weather Disaster
director:teamxtreme2           Operation: Eco-Nightmare
director:the7colors            The Seven Colors: Legend of PSY・S City
director:timmysafari           Timmy's Safari Adventure
director:tkkg1                 A Case for TKKG 1: Jennifer is Missing
director:tkkg2                 A Case for TKKG 2: Deadly Chocolate
director:tkkg3                 A Case for TKKG 3: The Mystery of the Mayan Treasure
director:tkkg4                 A Case for TKKG 4: The Secret of Dragon Claw Manor
director:tkkg5                 A Case for TKKG 5: TKKG Betrayed
director:tkkg6                 A Case for TKKG 6: The Forged Fifties
director:tkkg7                 A Case for TKKG 7: Fire!
director:tkkg8                 A Case for TKKG 8: The Captain's Legacy
director:tkkg9                 A Case for TKKG 9: Voodoo Magic
director:tkkg10                A Case for TKKG 10: Panic in a Boarding School
director:tkkg11                A Case for TKKG 11: Action!
director:tkkg12                A Case for TKKG 12: Alarm at the Roller Coaster
director:tkkg13                A Case for TKKG 13: Cell 13
director:tkkg14                A Case for TKKG 14: Dangerous Holiday
director:tommy                 Pete Townshend Presents Tommy: The Interactive Adventure
director:totaldistortion       Total Distortion
director:traitorsgate          Traitors Gate
director:travelrama            Travelrama USA
director:tweeniesrtp           Tweenies: Ready to Play
director:vcop                  Virtual Cop
director:vcop1                 Virtual Cop: Episode One: Good Cop / Bad Cop
director:vcop2                 Virtual Cop: Episode Two: The Angel Returns
director:veniceglass           Venice Under Glass
director:vjg                   Vegas Jackpot Gold
director:vnc                   Virtual Nightclub
director:vp2                   Virtual Physics: The Eggs of Time
director:vvcyber               Victor Vector & Yondo: The Cyberplasm Formula
director:vvdinosaur            Victor Vector & Yondo: The Last Dinosaur Egg
director:vvharp                Victor Vector & Yondo: The Hypnotic Harp
director:vvvampire             Victor Vector & Yondo: The Vampire's Coffin
director:wallobee              Wallobee Jack: The Bingi Burra Stone
director:wallobee2             Wallobee Jack: The Thai Sun Adventure
director:wallobee3             Wallobee Jack: The Lost Lionardo
director:wallobee4             Wallobee Jack: Secret of the Sphinx
director:wallobeetemple        The temple of Monakumba: Starring Wallobee Jack
director:warlock               Spaceship Warlock
director:wiggles1              A Day with the Wiggles
director:winniewitch           Winnie the Witch
director:wishbone              Wishbone and the Amazing Odyssey
director:wolfgang              Wolfgang the Cyberwolf
director:wrath                 Wrath of the Gods
director:xanthus               Xanthus
director:xfools                The X-Fools: The Spoof is Out There
director:xmasstory             A Christmas Story
director:y2lgeography          Yearn2Learn: Master Snoopy's World Geography
director:y2lmath               Yearn2Learn: Master Snoopy's Math
director:y2lsnoopycoloring     Yearn2Learn: Master Snoopy's Coloring Book
director:y2lflintcoloring      Yearn2Learn: The Flintstones Coloring Book
director:y2lpeanuts            Yearn2Learn: Peanuts
director:y2lsnoopy             Yearn2Learn: Snoopy
director:y2lspelling           Yearn2Learn: Master Snoopy's Spelling
director:ybr1                  Yellow Brick Road
director:9worlds               Nine Worlds hosted by Patrick Stewart
director:aamn                  Anatomy & Anaesthesia of the Mandibular Nerve
director:adamcmp               A.D.A.M. Comprehensive
director:adamess               A.D.A.M. Essentials
director:adamstd               A.D.A.M. Standard
director:adamtis               A.D.A.M. The Inside Story
director:alankay               Alan Kay CD-ROM Pack
director:alcohol101            Alcohol 101
director:alice2ocean           From Alice to Ocean: Alone Across the Outback
director:amhha                 All My Hummingbirds Have Alibis
director:amnesty               Amnesty Interactive
director:artintact             the complete artintact komplett
director:artmarcopatrito       The Art of Marco Patrito
director:aruba                 Aruba Interactive
director:athletics             International Athletics
director:babylon5int           Babylon 5 Interactive
director:battles               Battles of the World
director:beatexp               The Beat Experience
director:bettypage             Betty Page: The World of a Pin-Up Queen
director:beyondcyberpunk       Beyond Cyberpunk! A Do-It-Yourself Guide to the Future
director:bht                   A Brief History of Time: An Interactive Adventure
director:bioflix               BioFlix
director:biomorph              Biomorph Encyclopedia: Muybridge Revisited
director:blam                  BLAM!
director:blam2                 BLAM! 2
director:blam3                 BLAM! 3
director:blindrom              BlindRom 0.9: The Prototype
director:bowie                 JUMP: The David Bowie Interactive CD-ROM
director:browser               Browser: Artopolis 97
director:bugbook               The Multimedia Bug Book
director:canelect              Exploring Canada's Electoral System
director:cdphysics             CD Physics for Windows
director:cezanne               A is for ART, C is for Cezanne
director:cezannetour           Paul Cézanne Art Tours
director:chuniverse            The Challenge of the Universe
director:cinevolt              Cinema Volta: Weird Science & Childhood Memory
director:cocktailhour          Cocktail Hour: A Guide to Bartending
director:comusic               Computer Music: An Interactive Documentary
director:cpnre                 Canadian Practical Nurse Registration Exam Practice
director:ctrain                Doing it in C++
director:dailymail100          Daily Mail Centenary: 100 Amazing Years
director:delphi4tutor          Borland Delphi 4 Tutor
director:dinos                 Multimedia Dinosaurs
director:dynamichuman          The Dynamic Human: The 3D Guide to Anatomy and Physiology
director:easybass              Easy Bass
director:easyitalian           Easy Cooking Italian
director:edh                   Executive Diet Helper
director:egypt                 Egypt: Voyage to the Land of the Pharaohs
director:einstein              The Ultimate Einstein
director:elfascd               ELFAs CD - 1 september 1999
director:espanatomy            Anatomy & Physiology: The Unity of Form and Function
director:explorers             Explorers of the New World
director:flw                   The Ultimate Frank Lloyd Wright: America's Architect
director:fractiondecimal       Fractions & Decimals
director:frequency             frEQuency
director:fusion                Harnessing the Energy of the Stars
director:futureview            FutureView: The 1990s and Beyond
director:ghetto                Stories from the Warsaw Ghetto
director:golfcd                The Great Golf CD: Links, Legends & Lore
director:gp2006                Grand Prix 2006 & Auto Directory
director:guns                  Multimedia Guns
director:haight                Haight-Ashbury in the Sixties
director:heuther               Understanding Pathophysiology, 3rd Edition
director:hikaruhana            Shining Flower: Hikaruhana
director:hirezaudio            Hi Rez Audio
director:hunchback             The Secret of the Hunchback
director:ibmcdextra            Sony Music CD Extra Sampler
director:iptr                  I Photograph to Remember
director:isscommerce           International Space Station: Space Commercialization
director:itc                   Internet the City: A Guided Tour Through the Internet
director:journey2life          The Journey to Life
director:learningcoreldraw3    Learning CorelDRAW 3
director:laughingbird          The Laughing Bird Restaurant
director:learninternet         Video Professor: Learn to Use the Internet
director:learnworks2           Video Professor: Learn Works for Windows 95, Level 2
director:leonardo              Leonardo the Inventor
director:lewisclark            Lewis & Clark Interactive Picture CD
director:lifemysteries         Life's Greatest Mysteries
director:lifeuniverse          Life in the Universe
director:louvre                Le Louvre: The palace & its paintings
director:lovedisk              Lovedisk 95
director:makers                Makers of the 20th Century
director:mediabook             The MediaBook CD for Director
director:moag                  The Museum of Anything Goes
director:ms500nations          Microsoft 500 Nations
director:msa2001               Middle School Advantage 2001
director:msdinosaurs           Microsoft Dinosaurs
director:msoceans              Microsoft Oceans
director:mswine                Microsoft Wine Guide
director:mysteriousegypt       Mysterious Egypt
director:newslinks             ABC NewsLinks
director:nia4                  News in Action 4
director:nixon                 Nixon: Watergate
director:nmm                   Nine Month Miracle
director:nobel100              The Nobel Prize: 100 Years of Creativity and Innovation
director:painters              Emile de Antonio's Painters Painting
director:paris                 Paris: History and Splendour
director:parisvt               Virtual Tourism Paris
director:parliament            People & Parliament: A Stranger's Guide to Westminster
director:picasso               Picasso: the man, his works, the legend
director:pixar                 Pixar Projector
director:planetstrass          Pl@net
director:potala                1000 Years Potala
director:princetonsat98        The Princeton Review: Inside the SAT '98
director:revwar                Revolutionary War Picture CD
director:rodneyab              Rodney's Art Brain
director:saguaro               Saguaro & the City: Investigate the Sonoran Desert with an Interactive CD ROM
director:saillusion            Scientific American Library: Illusion
director:sagasoftworks         The Saga Softworks
director:sarahcatalog          Sarah McLachlan Catalogue
director:sauniverse            Scientific American Library: The Universe
director:sciencesmart          Science Smart
director:scrutiny              ScruTiny in the Great Round
director:sentence              this is a sentence
director:shiningflower         Shining Flower: HikaruHana
director:sialmanac94           Sports Illustrated 1994 Multimedia Almanac
director:sk8board              RIDE: An Interactive Skateboarding Experience
director:skieurope96           Ski Europe '96
director:smithamerica          Smithsonian's America
director:supersonic            Supersonic: A Multimedia Guide to Modern Military Aircraft
director:survive               How Would You Survive?
director:take5                 Take Five: Relaxation at Your Finger Tips
director:technik               Technology Interactive
director:texas                 A Virtual Reality CD-ROM Guide to Texas
director:theatreimag           Theatre of the Imagination
director:toyota95              1995 Toyota Interactive
director:trekchair             Star Trek: Captain's Chair
director:trekguideds9          Star Trek: Deep Space Nine Episode Guide
director:trekguidetng          Star Trek: The Next Generation Episode Guide
director:trekomni              Star Trek Omnipedia
director:trekpedia98           Star Trek Encyclopedia 1998
director:trekship              Star Trek: Starship Creator
director:trekshipaddon         Star Trek: Starship Creator Add-on Pack
director:trektech              Star Trek: The Next Generation Interactive Technical Manual
director:trekshipcreate        Star Trek: Starship Creator
director:truthsfictions        Truths & Fictions: A Journey from Documentary to Digital Photography
director:universe              Invisible Universe
director:unwrap                Unwrap the Magic: Holiday 2000 Interactive CD-ROM
director:ushistory             The History of the United States for Young People
director:venetiandeer          Venetian Deer
director:vote                  Vote America: Your Field Guide to Electing a President
director:vtarot                Virtual Tarot
director:vusic                 Vusic: The Screen Raver
director:wackyjacks            Wacky Jacks
director:warplanes             Warplanes: Modern Fighting Aircraft
director:webmaster             Webmaster: Fantastic Adventures in the World of the Internet
director:whales                World of Whales: An Interactive Voyage of Pure Wonder
director:wildblueyonder1       Wild Blue Yonder: Episode 1: 50 Years Of Gs And Jets
director:wine                  The Wine CD
director:withopeneyes          With Open Eyes: Images from The Art Institute of Chicago
director:womanengineer         You Can Be a Woman Engineer
director:woodstock25           Woodstock: 25th Anniversary CD-ROM: 3 Days of Peace & Music
director:worldnet              AT&T WorldNet Service E-Guide
director:wwanimals             Wide World of Animals
director:xfua                  The X-Files Unrestricted Access
director:expbooktoolkit2       Expanded Book Toolkit II
director:secretwriters         Secret Writer's Society
director:101pet                Dalmation Adoption
director:50ftchicken           Attack of the 50-foot Chicken
director:alanna                The Lost Island of Alanna
director:antfarm               Ant Farm
director:antsafire             Ants Afire!
director:aolstarwars           Star Wars: Episode III: Game, Videos & More!
director:arad                  Animaniacs River Adventure
director:belcher               The Belcher
director:bigsound              BigSound VW Player
director:bigtimemovie          Big Time Movie Studios
director:bingobuds             Bingo Buddies
director:bob                   Bob
director:broadwayyb            The 2000-2001 Broadway Series Interactive Yearbook
director:catseyeview           Cat's Eye View
director:childishgambino       Capturing Donald Glover's Motion
director:colormind             ColorMind
director:crybaby               Crying, Screaming Baby
director:dfireworks            The Digital Fireworks Stand
director:dreidel               DreidelLand: An Electronic Hanukah Treat
director:emigre                Emigre Signs of Type: Big Cheese
director:fortuneteller         The Fortune Teller
director:imision369            ImIsion 369
director:kfk                   Kung Fu Kim
director:letterrally           Letter Rally
director:limit0                Limit 0
director:makeamug              Make-A-Mug
director:makingmusic           Morton Subotnick's Making Music
director:mathtest              Math Test
director:missileattack         Missile Attack
director:namegame              Name that Game
director:njdevils2001          2001 New Jersey Devils Interactive CD ROM
director:nomis                 Nomis
director:nyknicks2000          NY Knicks 2000
director:nykshuffle            NYK Shuffle
director:nyyankeesyb           New York Yankees Interactive Yearbook
director:pfarrypuzzle          Paul Farry Puzzle
director:prangers1             PowerRangers Part 1
director:prangers2             PowerRangers Part 2
director:psych                 Psych: An Interactive Stress Buster!
director:saspurs2001           San Antonio Spurs 2001 Broadcast Screensaver
director:saspurs2005           San Antonio Spurs Internet Hot-links
director:scanmon               ScanMon
director:seinfeldondvd         Seinfeld on DVD
director:sensei                Sensei
director:simpsontrivia         The Simpsons Trivia
director:sonysampler           Sony Music Sampler
director:sorgato               Sylvain Sorgato's Drawings in variable color
director:summertime            Summertime
director:thematrix             The Matrix: Cinemas Everywhere June 11
director:timeline              TimeLine Animation
director:troubleshoot101       Troubleshooting 101
director:twine                 The World is Not Enough 007
director:verttice              DreamLight Verttice
director:wonkatrivia           Wonka Trivia
director:wriggle               Wriggle
director:avrilletgo            Avril Lavigne: Let Go
director:bobmambo5             Bob the Builder: Mambo No. 5
director:chaquico1000          Craig Chaquico: A Thousand Pictures
director:concentration         Solitudes: Natural Concentration
director:freakshowost          The Residents: Freak Show: Multimedia Bonus Track
director:gingerbreadman        The Residents: Gingerbread Man
director:girlsaloudbox         Girls Aloud: The Singles Box Set
director:ebntelebreakdown      EBN: Telecommunication Breakdown
director:im7s7s                Iron Maiden: Seventh Son Of A Seventh Son
director:imesceneryfish        I Mother Earth: Scenery and Fish
director:listen7up             Listen 7UP! Music Mix CD: Volume 1
director:nyack                 Nyack 11-Track Player
director:princerave            Prince: Rave Un2 the Joy Fantastic
director:relaxation            Solitudes: Natural Relaxation
director:relaxplayer           Solitudes: Natural Relaxation Audio Player
director:royksoppam            Röyksopp: Melody A.M.
director:sarahsurfacing        Sarah McLachlan: Surfacing
director:smashchillin          Smash Hits: Chillin' Out Summer 2001
director:songbird              Solitudes: Songbird Symphony
director:stressrelief2         Solitudes: Natural Stress Relief II
director:tonetrakker           Tone Trakker
director:abctrain              Alphabet Train
director:alhisab               هيا نتعلم الحساب والمفاهيم
director:anasheed              إسطوانة قطار القصص والأناشيد
director:futsoft               برامج تعليمية من شركة فيوتشر سوفت
director:hamamalachkal         تعلم مع همام الأشكال
director:hamamalalwan          تعلم مع همام الألوان
director:hamamalhuruf          تعلم مع همام الحروف
director:ktaralarkam           قطاد الأرقام
director:mesoftware            شركة الشرق الأوسط للبرمجيات
director:sakhr                 مجلة برامج صخر
director:3iadins               TV3 i a dins!
director:limit0inici           Límit 0 Inici
director:nemcina               Německá gramatika cvičebnice
director:bamse1                Bamses allerskoreste spille-rom
director:bamse2                Bamse: Min egen spille-rom
director:billetrille1          Bille & Trille: Da fantasien slap løs
director:billetrille2          Bille & Trille: Helt ude i skoven
director:brspel                BR spel
director:beestenboel           Beestenboel Zoölogic
director:boeboekshaboe         Boeboeks: Hop hop haboe!
director:boeboekstocht         Boeboeks: de toch naar opa Kakadoris
director:fcdk                  F.C. De Kampioenen: Op Zoek Naar Neroke
director:griezelbus1           De Griezelbus 1
director:kjoeties              Invasie van de Kjoeties
director:lannoo                Lannoo Nieuwe Media Demo
director:samson                Op Reis Met Samson & Gert
director:aapelin1              Aapelin ABC: Hurjistunut Pölynimuri
director:kcd                   Kompuutteri Kaikille
director:kultapossu            Kultapossu ja Leo Leijona: Sateenkaarivarkaat
director:petepilotti1          Pete Pilotti & Pontiac: Seikkailu Lapponiassa
director:1contre100            1 contre 100
director:affaires1             Affaires à suivre: L'Île diabolique
director:boulebill             Boule et Bill: Au Voleur!
director:boitearire            La boîte à rire
director:fg25ans               25 Ans! Le CD-ROM de Fluide Glacial
director:forestiajr            Forestia Révoltozoo
director:guignols1             Les Guignols de l'Info ... LE JEU!
director:guignols2             Les Guignols de l'Info: Le cauchemar de PPD
director:lvi                   La Vague Interactive
director:madmac                Mad Mac Cartoons
director:recfantome            Récréation fantôme
director:sethi2                Sethi et le sorcier inca
director:sethi3                Sethi et la Tribu de Neandertal
director:shadoks               Les Shadoks... Le jeu, la promenade
director:svmvillagina5         SVM Multimedia: Villagina 5
director:teddybear             Opération Teddy Bear
director:tomlisaindiens        Tom et Lisa: les Indiens
director:bibi2                 Bibi Blocksberg 2: Ein verhexter Schultag
director:bibifilm              Bibi Blocksberg: Mein verhextes Filmstudio
director:braingames            Brain Games
director:cklasse               Mercedes-Benz C-Class Information Booth
director:dieveteranen          Die Veteranen
director:dudenmeyer            Duden/Meyer Multimedia sampler
director:flaschenfahrrad       Das Verkehrs-Lernspiel: Fred und das Flaschenfahrrad
director:girlspack             Girl's Pack!
director:globiabc              Globi's ABC
director:janoschpanama         JANOSCH: Oh, wie schön ist Panama
director:janoschverkehr        JANOSCH: Tiger und Bär im Straßenverkehr
director:loewe1                Löwenzahn 1
director:loewe2                Löwenzahn 2
director:loewe3                Löwenzahn 3
director:loewe4                Löwenzahn 4
director:loewe5                Löwenzahn 5
director:loewe6                Löwenzahn 6
director:mats3                 Mats und das rätselhafte Tier
director:maus2                 Die CD-ROM mit der Maus 2
director:max1                  Max and the Secret Formula
director:max2                  Max and Marie Go Shopping
director:max3                  Max and the Haunted Castle
director:mrmore                Mr. More Interaktive
director:otelo                 o.tel.o Online 01011
director:ravensburger          Ravensburger Interactive Demo-Sampler
director:raveshuttle           Rave Shuttle: The Cosmic Challenge
director:ritterrost            Ritter Rost - Die Eiserne Burg
director:tkkgkit               TKKG: Identikit
director:zwergnase             Zwerg Nase: Ein interaktives Märchen
director:ironmask              The Iron Mask
director:lunes                 I Lunes e la sfera di Lasifer
director:magicanti             I Magicanti e i 3 elementi
director:robidoc               Robi & Doc: L'isola della Scienza
director:wolfgang              Wolfgang il Cyberlupo
director:4sight                four-sight
director:alexworld             ALeX-WORLD
director:alius                 The Alius: Intaractive Adventure Movie
director:angelgate             Angel Gate
director:animaltown            わくわくアニマルタウン
director:ankh1                 アンク ピラミッドの謎
director:ankh2                 アンク 2 ツタンカーメンの謎
director:ankh3                 アンク 3
director:apeodyssey            Ape Odyssey 2001
director:aramata               Aramata's Visual Wonderland: Magic of Perspective
director:atmarktown            Atmark Town
director:banddamashii          バンド魂
director:belzerion             Belzerion
director:bem                   妖怪人間ベム 新たなる魂の迷宮
director:bemtoybox             妖怪人間ベム データToyBox
director:beyondthetime         Beyond the Time
director:bombreikochiba        千葉麗子 BOMB!
director:cellofania            セロファニア
director:chinacrisis           China Crisis
director:chisanaensoka         小さな演奏家
director:choroli               The Trip of Choroli
director:christmassmallhouse   Christmastime at Small House
director:chuckletime           チャックルタイム
director:chuteng               中天
director:cutie10               キューティ１０
director:cookie                Cookie's Bustle: 謎のボンボワールド
director:cookieginger          Cookie & Ginger
director:crouton               Croûton
director:dan                   ダン
director:djrom                 The DJ-ROM: Da CD-Extra of Hip-Hop Music
director:digitalboy1           Digital Boy CD-ROM Vol. 1
director:digitalboy2           Digital Boy CD-ROM Vol. 2
director:digitalboy3           Digital Boy CD-ROM Vol. 3
director:dinoventure           The DinoVenture
director:dropcity              Drop City
director:dungeonstreet         Dungeon Street
director:nendo                 Digital Nendo
director:earthtia              アースティアサーガ ラーサーレジェンド
director:epson96               I Love EPSON '96 シェイプUPガールズ
director:erikotamuraoz         Eriko Tamura: Oz
director:fantazion             World Engine Fantazion
director:ffa                   ファンキー ファニー エイリアンズ
director:garyukeiba            我流競馬
director:ganbareinuchan        がんばれ！ いぬちゃん ロケンロール編
director:ganbareinuchan2       がんばれ！ いぬちゃん 世界の旅へん
director:gate1                 the GATE I 王国「MU」への扉
director:gate2                 the GATE II 王国「MU」への扉
director:gate3                 the GATE III 王国「MU」への扉
director:geraldmccoy           Detective Gerald McCoy
director:gocoo                 GO-COO
director:granmarmalade         グラン・マーマレード・マジカル・ビレッジ
director:henachoco             へなちょこダービー
director:henachoco02           サイテイバード
director:henachoco03           難しい本を読むと眠くなる
director:henachoco04           あの素晴らしい弁当を2度3度
director:henachoco04r          あの素晴らしいラメンスペシャル
director:henachoco05           野犬ロデム
director:henachoco06           蒸し蒸しチキンそり旅行
director:henachoco07           うそつきと私
director:henachoco08           おませなおませな屋台大作戦
director:henachoco09           ニセミジンコのうそひみつ
director:henachoco11           スロプロウエスタン
director:henachococd           ギャラクレヤン'75 オレニモインゼイクレヤン
director:henachocoexpo         イタチョコの野望
director:himejijo              A.MAZING姫路城
director:horrortour2           Zeddas: Horror Tour 2
director:horrortour3           ラビラーント
director:incarnatia            Incarnatia
director:ganguten              インタラクティブ玩具店
director:inugumi               犬組
director:ios                   iós
director:intro                 INTRO꞉ New Cultural EDGE Ver1.0
director:intro1                INTRO No. 1 1994
director:intro2                INTRO No. 2 1994
director:intro4                INTRO No. 4
director:jinkakuzukan          人格図鑑
director:junglepark            Jungle Park
director:jyajya                Jya jya
director:kamennoyakata         仮面の館
director:karuta                「フ・ジ・ワ・ラ・テ・イ・カ」の百人一首: かるたでおじゃる
director:katsumadojo           信光の勝馬道場
director:kazuyakun             数ヤ君
director:kenji                 Kenji
director:keroncuel             ウルトラリゾート ケロンキュール
director:kidsbox               Kids Box
director:kishido               棋士道
director:lzone                 L-ZONE
director:macaroni              マカロニほうれん荘 Interactive
director:macrotv               MACRO-TV
director:mamauta1              ママうたおう! 第一巻みんなともだち
director:maria                 MA-RI-A 人形館の呪い
director:marinefantasy         大方洋二の海中写真館 Marine Fantasy
director:mazebrew              MazeBrew
director:mecadrill             Mecadrill
director:mipeterwolf           ～Music Island Vol.1～　"ピーターと狼"
director:missihb               MISS Interactive Hard Boiled
director:momotaro              日本語探検シリーズ『方言ももたろう』
director:moworld               Reiko's Adventures in MO-World
director:mukashibanashi        日本昔話
director:multiakindo           マルチあきんど
director:murphystv             Murphy's TV
director:negi1                 ねぎ Vol. 1
director:negi3                 ねぎ3世
director:nihonchiri            Visual日本地理
director:niningashi            ににんがし
director:noahsark              Noah's Ark
director:nonta                 のんたくんとゆかいななかまたち
director:novacity              Nova City
director:orgotto               Orgotto
director:osaka1                必修大阪弁集中講座I 2010年、標準語は大阪弁になる
director:osaka2                必修大阪弁集中講座II 2015年、東京人の逆襲
director:overringunder         Over-Ring-Under
director:pantosstory           Pantos Story
director:pasosuke              ぱそすけ
director:peaceland             PeaceLand
director:peepeebonbon          Pee Pee Bon Bon
director:phantplanet           アミューズメント プラネット ファンタスマゴリア
director:phibos                フィボス ～彗星を追って～
director:picklesbook           Pickle's Book
director:pinkgear              Pink Gear Collection
director:pinkgear2             Pink Gear 2
director:planetdob             Planet Dob
director:poporon               PoPoRon
director:popup                 Pop Up Computer
director:popupmaker            Pop Up Maker
director:prescue               パラダイス レスキュ
director:pukapukarei           綾波育成計画 ぷかぷかレイちゃん
director:putlestory            Putlestory
director:pyramidint            Pyramid Interactive
director:racingdays            Racing Days
director:rad1                  RAD (Volume One)
director:refixion1             Refixion
director:refixion2             Refixion II: Museum or Hospital
director:refixion3             Refixion III トナカイストーリー
director:renderorgan           RenderOrgan
director:rheingold             ラインの黄金
director:rolypolys             ローリーポーリーズの七転び八起き
director:rolypolys2            ローリーポーリーズの世界旅行
director:ronron                ゆけゆけロンロン!
director:sabotenman            The Saboten Man
director:sakin2                砂金II
director:sakuratoasobo         さくらとあそぼ
director:schoolworld           A-L: Artificial Life: School World
director:seesawc1              SeesawC1
director:smallhouse            Small House
director:startover             Start Over ROM
director:tantei                完全探偵マニュアル
director:tenroutoshi           天楼都市 傀儡達の静宴
director:tetsuman              ハイ! 鉄マン です
director:tetsumangaiden        鉄マン外伝 ゲーム大王の野望
director:timegal               Time Gal
director:tokimemotype1         ときめきメモリアルタイピング
director:tokimemotypegs        ときメモGSタイピング
director:truegolf1             TrueGolf Part I
director:ttw                   Through the Window: In Search for the Lost Bag
director:twinbeeparadise       ツインビーPARADISE in どんぶり島
director:twistynight1          Twisty Night #1 合わせ月の夜
director:twistynight2          Twisty Night #2 フェンネル
director:twistynight3          Twisty Night #3 いにしえびと
director:ukiuki1               ウキウキ釣り天国 ～幻の天狗池～
director:ukiuki2               ウキウキ釣り天国2 ～波止の五目釣り～
director:ukiuki3               ウキウキ釣り天国3 ～人魚島のボート釣り～
director:ukiukiitsudemo        ウキウキ釣り天国 ～いつでもどこでも海釣り三昧～
director:ukiukistamp           うきうきスタンプ
director:ukyo1                 うきょー1
director:ursaminorblue         銀河の魚 URSA minor BLUE
director:victorianpark         Victorian Park
director:void                  VOID
director:vvs                   Virtual Variety Show
director:wackyraces            チキチキマシン猛レース ケンケンとブラック魔王のイジワル大作戦 Wacky Races
director:wariwari              わりわりワールド
director:wbz                   ウォーンバスター零
director:wrestlelife           レッスルライフ プロレス カードゲーム
director:xaxa                  XAXA MACHINE
director:ybr2                  イエロー・ブリック・ロードII
director:ybr3                  Yellow Brick Road ハラペコ月と星あつめ
director:yoidon                よ〜いドン!
director:yoshimotogeino        吉本芸能整形
director:zaibatsu              財閥銀行
director:a5tours               A5 Tours: Special Data Library
director:anony                 Anony
director:aumhodozenkiroku      「オウム」報道全記録 1989〜1995
director:allthelunar           オール・ザ・ルナ LUNAR -ハイパーアプリケーションズ-
director:angelolatrie          Jean Cocteau: Angélolatrie & Phénixologie
director:aozoragaho            青空画報
director:aquaplanet            Aquaplanet
director:aquazone              Aquazone
director:asylum300             Asylum 300
director:atmos                 Atmos Tetsujin Re-Mix
director:bakavideodrug         バカビデオドラッグ
director:chunchunworld         Chun-Chun World
director:clockkero             ケロ時計
director:clocksakura           さくら時計
director:clocktomoyo           知世時計
director:curiocity             キュリオシティ
director:cdromfanmacworld96    CD-ROM Fan MacWorld Expo Tokyo '96 Special Edition 
director:ddoa                  どきどき ON AIR ドラマシリーズ
director:delaware              Delaware: Catalog of Artoon
director:delphinokioku         デルフォイの記憶
director:digitalgips3          Digital GIPS Vol. 3
director:doshifunspecial       Doshi-Fun Special
director:dothereggae           Do the Reggae
director:doubutsushokai        どうぶつ紹介ﾌﾟﾛｼﾞｪｸﾀ
director:ebisu                 カンタンな人生の法則
director:eguchi                江口寿史 CG MUSEUM
director:fantasystudio         Fantasy Studio
director:fototune              FotoTune Multimedia Show
director:fukuda                Fukuda Shigeo Retrospective Collection
director:furbydentaku          ファービー電卓
director:futarinoryori         ふたりの料理物語
director:futurepromotion       Towa Tei: Future Promotion
director:gasbook               GASBOOK
director:gasbook2              GASBOOK 002
director:gasbook3              GASBOOK 3
director:gasbook4              GASBOOK vol. 4: Gas City
director:gasbook5              GASBOOK 5: Paradise
director:gasbook6              GASBOOK 6
director:gasbook7              GASBOOK 7
director:gasbook8              gasbook8
director:gecrs                 GECRS - Guitar Education CD-ROM System
director:glassyocean           Glassy Ocean: original graphics & music
director:goalrush1             Goal Rush!!
director:goalrush2             Goal Rush!! 2 ～戦術分析編～
director:heididentaku1         ハイジ電卓１
director:heididentaku2         ハイジ電卓２
director:heididentaku3         ハイジ電卓３
director:heidimail             Heidi グリーティングメールカード
director:heidislide            Heidi スライドショー
director:hibino                Katsuhiko Hibino Interactive Exhibition
director:humanbody             The Human Body
director:illustratorsamerica   Illustrators in America
director:inuchanvalentine      いぬちゃんバレンタイン
director:inuchanfighter        いぬちゃんファイタ−
director:inuchanmovieparody    デジタルまんが いぬちゃん ナチュラルボーンクラーズ
director:ioshow                iós How To Game
director:japanart04            Japan Art Today 04
director:japanart07            Japan Art Today 07 村上隆「ロマンスの夕べ」展
director:jinseiproresu         人生プロレス
director:keiri                 経理入門
director:llla                  Live Love Life AIDS
director:mazebox               The Latest Works of MazeBox
director:macintosho20          村上隆
director:microphonefiend       Microphone Fiend
director:mmedia11              Masters of Media: The Making of サクラ大戦
director:moderntimes           Charles Chaplin in Modern Times
director:mominoki              もみの木の下で ～ The Day of St.Claus
director:monja                 monja
director:morisawa              人間と文字
director:moritaka              森高千里 CD-ROM 渡良瀬橋
director:msseifuku             ミッションスクール制服図鑑
director:musicforliving        Music for Living Sound
director:ngeeva00pf            Neon Genesis Evangelion: EVA-00 Paper Figure
director:no                    NO
director:nycalling             N.Y. Calling
director:oceansbelow           Oceans Below
director:pbdisplay             PerfectBLUE DISPLAY
director:pbflash               PerfectBLUE FLASH
director:pbmima                PerfectBLUE MIMA
director:pbosakana             PerfectBLUE OSAKANA
director:pbtoilet1             PerfectBLUE TOILET1
director:pbtoilet2             PerfectBLUE TOILET2
director:pepperon              ペペロン村の四季
director:perfectblue           Perfect Blue そらいろ★ナイト
director:please                Please!
director:pod1                  POD: Super Pop Digital Magazine
director:pod3                  POD: Super Pop Digital Magazine Vol. 3
director:pod4                  POD: Super Pop Digital Magazine Vol. 4
director:pod5                  POD: Super Pop Digital Magazine Vol. 5
director:pod6                  POD: Super Pop Digital Magazine Vol. 6
director:pod7                  POD: Super Pop Digital Magazine Vol. 7
director:pod8                  POD: Super Pop Digital Magazine Vol. 8
director:pod9                  POD: Super Pop Digital Magazine Vol. 9
director:previewreprise        Preview & Reprise: Haruhiko Shono
director:pyrethrum1            除虫菊Vol.1
director:randomdot             Random Dots
director:sakurascr             さくらのSCRセレクタ
director:satodesign            The Art of Computer Designing: A Black and White Approach
director:satohomosexual        Homosexual
director:sculpt4d              Sculpt 4D
director:shinshofukei          心象風景
director:spawncollection       Spawn Figure Collection for Windows 95
director:ssheidi1              Heidi スクリーンセーバー 1
director:ssheidi2              Heidi スクリーンセーバー 2
director:sskero                ケロ Screen Saver
director:sssakura              さくら Screen Saver
director:ssyamazaki            山崎君 Screen Saver
director:ssyukito              雪兎さん Screen Saver
director:syzygys               SYZYGYSｸﾘｯｸｱﾆﾒ｢ｽﾓｳ組曲｣
director:tokon5                闘魂V: 長州 力
director:tomato                To. Ma. To.
director:tree                  Onyx Tree Pro
director:tri3dtrial            Tri-3D-Trial
director:ukiukibgv             ウキウキ釣り天国 BGV
director:undergroundaz         Underground AtoZ SO OUT
director:vcb                   Virtual Cocktail Bar 200種類のカクテルのデータベース
director:vcbe                  Virtual Cocktail Bar Executive
director:virtualmuseum         Virtual Museum
director:xmaspresent           Christmas Present
director:yokaanime18           よかアニメ18発！
director:yokai                 真・百物語: 妖怪紳士録
director:yokai200              水木しげるの妖怪図鑑 傑作200選 -日本編1
director:yokai400              水木しげるの妖怪図鑑 傑作400選 -日本編2
director:yokaizukan            妖精妖怪図鑑
director:yumemirukairo         「夢みる廻廊」所幸則フルカラーミュージアムCD-ROM
director:zuiyomail             ZUIYO グリーティングメールカード
director:backgrounds           Backgrounds for Multimedia Series
director:bakkunooni            VOLT-AGE バックの鬼 -侘-
director:bandaipreviews3       1995 Bandai Visual CD-ROM Previews かわら盤 Vol. 3
director:bebox                 BeBox
director:businessmanager       琢磨 BusinessManager
director:calling               Calling
director:cnl                   City Net Line
director:creativeeye           Creative EYE
director:fontfriends           フォントフレンズ
director:greetingstudio        Greeting STUDIO
director:hypercardlessons      HyperCard Lessons
director:hypermaterial         Hyper Material
director:imgimpact             Images with Impact!
director:inposition            INposition
director:intelligentnote       インテリジェントノート
director:inuchancd             いぬちゃんのうたＣＤデモ
director:jointnet              JOINT-net
director:koyosha               Koyosha CD-INSPIREシリーズ
director:kpt                   Kai's Power Tools for Photoshop
director:macbasic              MacBASIC: Learning BASIC on HyperCard
director:maczaurus             Sharp Mac-Zaurus
director:negishihomes          Negishi Homes 建築見積ｿﾌﾄ
director:nsxpress              Honda NSX Press CD-ROM
director:olnet                 Open Library
director:picturecard           絵カード訓練システム
director:pipcatalog            PiPPiN Title CD-ROM Catalog
director:presenpack            Director PresenPack
director:pressit               PRESSiT
director:provektor2            Provektor II: Design & Image Library
director:provektor3            Provektor III: Design & Image Library
director:provektormed          Provektor Media
director:scripting             Macromedia Director Lingo Scripting Technology
director:secretsafari          Secret Safari
director:shadeviewer           Shade Viewer
director:sozaijiten            素材辞典
director:strata                Strata Studio Pro
director:toeic                 PowerTOEIC
director:toonet11              TooNet11
director:transland             トランスランド
director:wonderompm            アルダスページメーカー4.5J速習用CD-ROM
director:wonderomcw            WONDEROM クラリスワークス
director:voyagerkids           ボイジャーのキッズ CD-ROM
director:norgesjakten          Norgesjakten
director:kontyngent99          Katalog Samochodów Kontyngent '99
director:almabril98            Almanaque Abril 1998
director:bigmax                Revista BigMax
director:bpapao                A Turma do Bicho-Papão
director:divertire             Revista Divertire
director:irpf2002              Tutorial do IRPF 2002
director:kinderkit             Kinder-Kit
director:lobomau               As Histórias do Lobo Mau
director:objetivo              Astrologia e Geografia Objetivo
director:ratinho               Programa do Ratinho
director:engl                  English for Beginners
director:max1max2              Макс демонстрация
director:plcd                  Подводная Лодка
director:tchaik                Пётр Ильи́ч Чайко́вский: Жизнь и творчество
director:tutti                 Волшебные истории Тутти
director:123habloingles        1·2·3 Hablo Inglés
director:abrapalabra           Abrapalabra: La Magicia de Aprender a Leer
director:clasplusbee2          Classical Plus: Ludwig van Beethoven
director:deportes              Deporte y Musculación
director:eso                   ESO Essentials: Student's Interactive CD-ROM
director:inventos              Grandes Inventos
director:pcplus64              PC Plus Super CD 64
director:supermente            Super Mente
director:unlimitedcl           Unlimited CD-ROMs Educativos
director:alfons                Alfons Åberg ”Bara Överallt!”
director:acneattack            Acne-Attack!
director:backpacker2           Backpacker 2
director:backpackerjrdiy       BackPacker Junior - Do-It-Yourself
director:ernie                 Ernie: Broke in Bayonne
director:garygadget2           Bygg båtar med Mulle Meck
director:garygadget3           Bygg flygplan med Mulle Meck
director:garygadget4           Bygg hus med Mulle Meck
director:garygadget5           Upptäck rymden med Mulle Meck
director:historia              Svensk historia: från asatro till frihetskrig år 800-1500
director:jonssonligan1         Jönssonligan: Jakten på Mjölner
director:jonssonligan2         Jönssonligan går på djupet
director:mumin1                Kurragömma med Mumintrollen
director:onsalakorv            Onsalakorv
director:pettson1              Pettson o Findus i snickarbon
director:pettsonjk             Pettson o Findus julkalender
director:pettson2              Pettson & Findus i trädgården
director:pettsonjs             Pettsons julspel
director:pettson3              Pettson o Findus och mucklornas värld
director:pettson4              Pettson & Findus Spökskrämmarmaskinen
director:polis1                Polis
director:polis2                Polis 2: Någon ljuger
director:polis3                Polis 3: Vargspår
director:requiem               Requiem: en mordgåta på 1600-talet
director:rymdjakten            Rymdjakten
director:xtown1                CrossTown: Giftet
director:xtown2                CrossTown: Ängeln
director:ypl2                  勇者泡泡龍2
director:creativenursery       创意学前华丈(一)
director:amgpremiere           The American Girls Premiere
director:darylfgates           Police Quest Q&A with Daryl F. Gates
director:dcanyoncd             Dino CD Audio Player
director:freeallangels         Ash: Free All Angels Video Mixer
director:klingonlab            Klingon Language Lab
director:lbfamfun              Little Bear Family Fun
director:picarddossier         Mini-Omnipedia: Picard Dossier
director:poliq                 Political IQ Test
director:pqmakingof            The Making of Police Quest
director:scissorsnstones       Scissors N Stones On-Line Manual
director:solmahjong            Solitudes Mahjong Game
director:superbowltrivia       Super Bowl Trivia Game
director:thinkinthingsdp       Dear Parents: About Thinkin' Things...
director:ultrobotkit           Robotoid Assembly Toolkit
director:ultrobotss            Screen Saver Viewer
director:williamsbts           Williams Arcade Classics: Behind the Scenes
director:planetrav             Planetary Traveler
director:encarta94             Microsoft Encarta '94
director:encarta95             Microsoft Encarta '95
director:encartaatlas2000      Microsoft Encarta Interactive World Atlas 2000
director:exoticjapan           Exotic Japan: A Guide to Japanese Culture and Language
director:famdoc3               The Family Doctor, 3rd Edition
director:macworldexpo92        Macworld Expo CD Boston 1992
director:manhole               The Manhole
director:mazewars              Maze Wars+
director:mmmozart              Multimedia Mozart: The Dissonant Quartet
director:mmschubert            Multimedia Schubert: The "Trout" Quintet
director:osmo                  Cosmic Osmo and the Worlds Beyond the Mackerel
director:shatter               Shatter by Mike Saenz
director:spelunx               Spelunx and the Caves of Mr. Seudo
director:stravinsky            Igor Stravinsky: The Rite of Spring
director:blender               Blender: The Pop Culture Magazine on CD-ROM
director:blenderbest           Best of Blender: The Interactive Entertainment Magazine
director:cmi                   Computer Music Interactive
director:gamingmegapac         MacUser Presents Gaming MegaPac
director:godigital             Go Digital Interactive Magazine
director:insidemacgames        Inside Mac Games
director:interactivemagic      MacUser Mac Interactive Magic
director:iwave                 Interactive Wave
director:maccubed7             MacCubed Disc 7: Internet & Utilities
director:macsca                Mac S.C.A. Magazine
director:macweekvideo          MacWEEK Guide to Desktop Video
director:mieuxmieux            Le CD-ROM Mac Mieux-Mieux
director:mindvirus             Mindvirus
director:mobiclic              Mobiclic
director:pcformat              PC Format
director:pcwuk                 Personal Computer World
director:stream                Digital Culture Stream Magazine
director:aaha2007              AAHA! Denver 2007: It's Different Here!
director:adamcatalog           The A.D.A.M. 1994 Catalog
director:adamscholar           The A.D.A.M. Scholar Series
director:applestore            Apple Company Store
director:aptesampler           APTE Product Sampler
director:arcmedia              Arc Media Demos
director:blaster               Blaster Series Demo
director:bpmc                  Byron Preiss Multimedia Catalog
director:cmc                   Creative Multimedia Catalog
director:coreltour             Corel Product Tour
director:davidsonpp            Davidson Product Previews
director:davidsonps            Davidson Product Sampler
director:disneyint             Disney Interactive presents Learning & Creativity Sampler Volume I
director:disneylearning        Disney Interactive Learning Sampler
director:dkmm2                 Dorling Kindersley Multimedia Sampler Disc 2
director:edmark                Edmark Demo
director:emme                  E.M.M.E. Interactive: The Keys to Knowledge
director:eureka                Eureka Multimedia Promo
director:fppuddlebooks         Fisher-Price Read & Play: Puddle Books Demos
director:fpready               Fisher-Price Ready for School Demo
director:grolier               Grolier Products
director:gusbuds               Gus and the CyberBuds Learning Adventure Series
director:headbone              Headbone CD-ROM Sampler
director:hoffman               H+a Collection
director:ilearn                iLearn
director:imagineers            The Imagineers
director:imaginopolis          Microsoft Imaginopolis
director:incoming              iNCOMING
director:iona                  Iona Software Demo CD
director:ipc                   About InterActive Publishing
director:jsa                   JumpStart Advanced: How Does Your Child Learn Best?
director:jslearn               JumpStart Learning System
director:kidtools              Kid Tools Series Demo
director:learningsystem        The Learning System
director:maxissampler          Maxis CD-ROM Sampler
director:mcdonaldland          Mission to McDonaldland
director:msgfromapple          Message from Apple
director:newton                World of Newton
director:origin                Origin Systems Product Catalog
director:playskool             Playskool Software Experience CD-ROM Sampler
director:poohlearn             Disney Learning Winnie the Pooh Demos
director:rh                    Rescue Heroes Demo
director:sfk                   Science for Kids Product Demos
director:tlc                   The Learning Company Sampler
director:ubt                   Under the Big Top
director:vygrpresents          Voyager Presents
director:wti                   Workstation Technologies Inc: The Digital Video Company
director:3datlas97             3D Atlas 97
director:3datlas98             3D Atlas 98
director:adobedimensions       Professional Tips for Adobe Dimensions
director:agfa                  AgfaType
director:aol                   America Online
director:ataripack             Activision's Atari 2600 Action Pack
director:balto2                Balto II: Wolf Quest
director:baseballhits          Baseball's Greatest Hits
director:bcsinkfloat           Blue's Clues: Sink and Float
director:blockbuster2          Blockbuster Guide to Movies & Videos, 2nd Edition
director:bobteam               Bob the Builder: Teamwork
director:bookshelf94           Microsoft Bookshelf 1994
director:c64pack               Activision's Commodore 64 15-Pack for Windows
director:cfdemo                The ClueFinders Demo
director:cinemania94           Microsoft Cinemania 94
director:cinemania95           Microsoft Cinemania 95
director:cinemania96           Microsoft Cinemania 96
director:clarisimpact          ClarisImpact
director:clarisworks           ClarisWorks
director:compton               Compton's Interactive Encyclopedia 1995 Edition
director:cpu                   Connectix PowerBook Utilities
director:cricketdraw           CA Cricket Draw III
director:d                     D
director:dinosafari            Dinosaur Safari
director:dotsafe               Dotsafe
director:earthwormjim          Earthworm Jim
director:exos                  Exos PowerStick
director:explorapedia          Microsoft Explorapedia
director:famalbum              Family Album Creator
director:famdoc4               The Family Doctor, 4th Edition
director:freehand              Aldus FreeHand 2.0
director:geoquery              Odesta GeoQuery
director:greeneggs             Green Eggs and Ham
director:hollywoodhigh         Hollywood High
director:hyperblade            HyperBlade
director:ideacomm              IDEAcomm Mac
director:iliad                 Iliad
director:illustrator           Adobe Illustrator
director:landdesigner          Sierra Land Designer
director:lbt8                  The Land Before Time: The Big Freeze
director:leopardspots          How the Leopard Got His Spots
director:lion                  Lion
director:lotus123              Lotus 1-2-3
director:macos8                Mac OS 8
director:macportable           Your Apple Tour of the Macintosh Portable
director:mathblasterjr         Math Blaster Jr.
director:mavisbeacon           Mavis Beacon Teaches Typing
director:mechwarrior2          MechWarrior 2
director:meetingmaker          Meeting Maker
director:mindbrain             The Lost Mind of Dr. Brain
director:mothergoosehires      Mixed-Up Mother Goose Deluxe
director:msaccess              Microsoft Access
director:msarcade              Microsoft Arcade
director:msartgallery          Microsoft Art Gallery
director:msautomap             Microsoft Automap Road Atlas
director:msbaseball            Microsoft Complete Baseball
director:msbasketball          Microsoft Complete Basketball
director:msbob                 Microsoft Bob
director:msbhumanbody          Scholastic's The Magic School Bus Explores the Human Body
director:msbsolarsystem        Scholastic's The Magic School Bus Explores the Solar System
director:mscomposers           Microsoft Illustrated Interactive Composer Series
director:msdogs                Microsoft Dogs
director:msexcel               Microsoft Excel
director:msflight              Microsoft Flight Simulator
director:msfonts               Microsoft TrueType Font Pack
director:msgolf                Microsoft Golf
director:msmoney               Microsoft Money
director:msmouse               The Microsoft Mouse
director:msmouseh              Microsoft Home Mouse
director:msmusint              Microsoft Musical Instruments
director:msn                   The Microsoft Network
director:msnatkey              Microsoft Natural Keyboard
director:msoffice              Microsoft Office
director:mspowerpoint          Microsoft PowerPoint
director:msproject             Microsoft Project
director:mspublish             Microsoft Publisher
director:mspublishd            Microsoft Publisher Design Packs
director:msschedule            Microsoft Schedule+
director:mssndbits             Microsoft SoundBits
director:msword                Microsoft Word
director:msworks               Microsoft Works
director:muppets               Muppet Treasure Island
director:musiccentral96        Microsoft Music Central 96
director:musicpublisher        Graphic Notes Music Publisher
director:netmarket             CUC netMarket Demo
director:ofoto                 Light Source Ofoto
director:orly                  Orly's Draw-A-Story
director:pagemaker             Aldus PageMaker
director:pitfall               Pitfall: The Mayan Adventure
director:powerchess            Power Chess
director:princeint             Prince Interactive
director:pspice                MicroSim PSpice
director:ramdoubler            RAM Doubler
director:raydream              Ray Dream Designer
director:readblasterjr         Reading Blaster Jr.
director:redshift              RedShift: Multimedia Astronomy
director:rosettastone          The Rosetta Stone
director:santafe1              Santa Fe Mysteries: The Elk Moon Murder
director:shanghai              Shanghai: Great Moments
director:smashsounds1          Smash Sounds Volume 1
director:spycraft              Spycraft: The Great Game
director:system7smash          System 7 is a SMASH!
director:thetowerxmas          TOWER/CD ~Christmas Disc~
director:timelapse             Timelapse
director:trekfinalunity        Star Trek: The Next Generation - "A Final Unity"
director:ultrobot              Isaac Asimov's The Ultimate Robot
director:wep                   The Best of Microsoft Entertainment Pack
director:windows31             Microsoft Windows 3.1
director:wfw31                 Microsoft Windows for Workgroups 3.1
director:windows95             Microsoft Windows 95
director:worldatlas            World Reference Atlas
director:wpmainstreet          WordPerfect Main Street
director:wttf                  Welcome to the Future
director:xfiles                The X-Files
director:znemesis              Zork Nemesis: The Forbidden Lands
director:zoombini              Logical Journey of the Zoombinis
director:barbssbubbles         Barbie Screen Styler: Bubbles
director:barbsskisses          Barbie Screen Styler: Kisses
director:barbssshoes           Barbie Screen Styler: Shoes
director:billetrille1ss        Bille & Trille 1 Screen Saver
director:cinemac               CineMac Screen Saver Factory
director:globiss               Globi's Bildschirmschoner
director:lewisclarkss          Lewis and Clark Screen Saver
director:nekojiruudonss        Nekojiru Udon Screen Saver
director:nightrider            Night Rider
director:photos4us             Photos4us
director:pingufight            Pingu Snowball Fight
director:pingufish             Pingu Fish Chase
director:pinguss               Pingu Screen Savers
director:pingustorm            Pingu Snow Storm
director:pingustunt            Stunt Pingu
director:pingutime             Time for Pingu
director:ss007                 The James Bond Screensaver
director:ss102dalmations       102 Dalmations Screen Saver
director:ssbeastie             Beastie Boys ScreenSaver
director:ssbudfranklouie       Budweiser: Frank & Louie Screen Saver
director:sscocacola            Coca-Cola Screen Saver
director:ssdietcoke            Diet Coke Screen Saver
director:ssgbi                 German Bold Italic Screen Saver
director:sshercules            Hercules: The Legendary Journeys Screen Saver
director:sshighlander          Highlander: The Screen Saver
director:ssholidaymickey       Holiday Mickey Screen Saver
director:ssleepipes            The Lee Pipes Desktop Animated Feature
director:sslivepicture         Live Picture Screen Saver
director:ssnatureasart         Nature as Art
director:sspeekaboo            Winnie the Pooh Peek-a-Boo Screen Saver
director:ssrevwar              Revolutionary War Screen Saver
director:ssseven               Seven Screen Saver
director:tamafridgi            TamaFridgi
director:bvi1997               Buena Vista International 1997 Promotional Interactive CD-ROM
director:bluesbros2000         Blues Brothers 2000 Full Promotion
director:easports2000          EA Sports_2000 (E3 1999)
director:hoaddams2             Hollywood Online: Addams Family Values
director:hoangus               Hollywood Online: Angus
director:hodolores             Hollywood Online: Dolores Claiborne
director:horobroy              Hollywood Online: Rob Roy: Legend of the Mist
director:hostargate            Hollywood Online: Stargate
director:hothenet              Hollywood Online: The Net
director:leepipes              Lee Pipes Press Kit
director:mulanpresskit         Mulan Multimedia Press Kit
director:stalker               S.T.A.L.K.E.R.: Shadow of Chernobyl
director:thesims               The Sims Electronic Press Kit
director:vug2005               Vivendi Universal Games 2005 E3 DPK
director:westwood              Westwood Studios Digital Press Kit 2000
director:busty3                Busty Babes Volume III
director:busty4                Busty Babes Volume IV
director:csa                   Cyber Sex Angel
director:cyberphoto            CyberPhotographer
director:dancinggals           Dancing Gals Power
director:digerotica            Digital Erotica
director:digitalogue           Digitalogue Home Museum Series
director:dmj5                  DMJ5: The Game!
director:dmpgallery            Digital Magazine for Photography: Gallery
director:dream1                The Dream Machine: The Virtual Sexual Experience
director:dream2                The Dream Machine 2
director:eros                  Fischer's Erotic Encyclopedia
director:gilgameshnite         ギルガメッシュ Night Super Deluxe CD-ROM
director:historiapoca          A História Não Contada de Pocahontas
director:houseparty            House Party: The Game
director:immorale              Immorale
director:isswim98              Inside Sports 1998 Swimsuit Issue
director:labyrinth             Labyrinth
director:legs                  Legs
director:macplaymate1          MacPlaymate
director:macplaymate2          MacPlaymate II
director:neurodancer           NeuroDancer
director:nightnurses           Nightshift Nurses: The Game
director:pbvv                  Playboy's Voluptuous Vixens
director:playmate1999          1999 Playboy Playmate Calendar
director:sadowar               RSP
director:scop                  Scop
director:shock                 Shock: The Game
director:sororitystwrdss       Sorority Stewardesses
director:thebody               The Body: Five doors plus
director:thelegs               The Legs ～Get a LEG up～
director:timewarp              Time Warp
director:venus                 Venus Photo CD-ROM
director:vpeepshow             Virtual Peep Show
director:vsex1                 Virtual Sex
director:vsex2                 Virtual Sex II
director:vsexasia              Virtual Sex with Asia
director:vvalerie1             Virtual Valerie
director:vvalerie2             Virtual Valerie 2
director:vvaleriedc            Virtual Valerie: Director's Cut
director:vveronika             Virtual Veronika
director:vvs1                  Supermodels: Virtual Video Shoot
dm:dm                          Dungeon Master
draci:draci                    Draci Historie
dragons:dragons                Blazing Dragons
drascula:drascula              Drascula: The Vampire Strikes Back
dreamweb:dreamweb              DreamWeb
glk:Adrift                     Adrift IF Game
glk:1sttime                    1st Time
glk:3monkeys                   Three Monkeys, One Cage
glk:adriftorama                ADRIFT-O-Rama
glk:adventurestrikes           Adventure Strikes When You Least Expect It
glk:akron                      Akron
glk:albridgemanor              Albridge Manor
glk:ascot                      The Ascot
glk:asdfa                      A Short Damn Fantasy Adventure
glk:awalkatdusk                A Walk At Dusk
glk:bariscebik                 Bariscebik
glk:barneysproblem             Barney's Problem
glk:beanstalk                  Beanstalk the and Jack
glk:beerisntenough             When Beer Isn't Enough
glk:caveofwonders              Cave of Wonders
glk:circusmenagerie            Menagerie!
glk:cityInfear                 City In Fear
glk:coloromcadrift             Color of Milk Coffee
glk:compendiumendgame          The Woodfish Compendium: The Game to End All Games
glk:compendiumforum            The Woodfish Compendium: Forum
glk:compendiumforum2           The Woodfish Compendium: Forum2
glk:compendiumimagi            The Woodfish Compendium: ImagiDroids
glk:compendiumsaffire          The Woodfish Compendium: Saffire 
glk:compendiumtopaz            The Woodfish Compendium: Topaz
glk:cowboyblues                Cowboy Blues
glk:crawlersdelight            Crawler's Delight
glk:crimeadventure             Crime Adventure
glk:cursed                     Cursed
glk:cyber1                     Cyber Warp 1
glk:cyber2                     Cyber Warp 2
glk:darkness                   Darkness
glk:datewithdeath              A Date with Death
glk:dayattheoffice             A Day at the Office
glk:deadreckoningadrift        Dead Reckoning
glk:dontgoadrift               Don't Go
glk:doortoutopia               The Door to Utopia
glk:driftingin                 Adrift Drifting In
glk:drwhovortexlust            Doctor Who and The Vortex of Lust
glk:edithscats                 Edith's Cats
glk:enc1                       Encounter 1 : Tim's Mom
glk:enc2                       Encounter 2 : The Study Group
glk:escapetofreedom            Escape to Freedom
glk:etnyadrift                 Escape to New York
glk:farfromhome                Far From Home
glk:finedayforreaping          A Fine Day for Reaping
glk:frustratedinterviewee      Frustrated Interviewee
glk:gammagals                  The Gamma Gals
glk:ghosttownadrift            Ghost Town
glk:gmylm                      Give Me Your Lunch Money
glk:goldilocksadrift           Goldilocks is a FOX!
glk:halloweenhijinks           Halloween Hijinks
glk:houseofthedamned           House of the Damned
glk:suzygotherpowers           How Suzy got her Powers
glk:hcw                        How to Conquer the World
glk:inthemind                  In The Mind Of The Master
glk:irvinequik                 Irvine Quik & the Search for the Fish of Traglea
glk:jgrim                      Jonathan Grimshaw: Space Tourist
glk:jimpond                    Jim Pond 1
glk:lairofthevampire           Lair of the Vampire
glk:legacyofaprincess          Legacy of a Princess
glk:longjourneyhome            The Long Journey Home
glk:lostadrift                 Lost
glk:magicshow                  The Magic Show
glk:maroonedadrift             Marooned
glk:ml256                      Makers Local and the Transdimensional Margarita Blender
glk:monsterage                 Monster Age: Trials of Dustorn
glk:monsters                   Monsters
glk:mortality                  Mortality
glk:murdererhadleft            What The Murderer Had Left
glk:mustescape                 Must Escape!
glk:mymindsmishmash            My Mind's Mishmash
glk:neighboursfromhell         Neighbours From Hell
glk:onnafa                     Oh No, Not Another Fantasy Adventure
glk:overtheedge                Over the Edge
glk:partytomurder              A Party to Murder
glk:pathwayadrift              Pathway to Destruction
glk:pestilence                 Pestilence
glk:phonebooth                 Pick Up the Phone Booth and Cry
glk:pkgirl                     The PK Girl
glk:plagueredux                The Plague - Redux
glk:praxis                     from the Files of Sigmund Sigmund Praxis, Guerrilla Therapist
glk:ptbad65                    PTBAD6.5: THE URL THAT DIDN'T WORK
glk:ptgood                     PTGOOD
glk:professorvonwitt           Professor von Witt's Fabulous Flying Machine
glk:provenance                 Provenance
glk:rachelbadday               Rachel has a bad day
glk:readinginmayadrift         A Reading in May
glk:requiem                    Requiem
glk:sceneofthecrime            Scene of the Crime
glk:selmaswill                 Selma's Will
glk:seymoursstoopidquest       Seymour's Stoopid Quest
glk:skybreak                   Skybreak!
glk:sommeril                   Sommeril
glk:sophia                     Sophia
glk:spaceboy                   The Adventure of Space Boy!
glk:stowaway                   Stowaway
glk:superheroday               A Day In The Life Of A Super Hero
glk:takeone                    Take One
glk:target                     Target
glk:thepkgirl                  The PK Girl
glk:viewisbetter               The View Is Better Here
glk:thelasthour                The Last Hour
glk:thesisters                 The Sisters
glk:thevirtualhuman            The Virtual Human
glk:hellinahamper              To Hell in a Hamper
glk:toomuchexercise            Too Much Exercise
glk:topaz                      Topaz
glk:twilight                   The Twilight
glk:unauthorizedtermination    Unauthorised Termination
glk:unfortunately              Back To Life... Unfortunately
glk:unravelinggod              Unraveling God
glk:vague                      Vague
glk:vendetta                   Vendetta
glk:veteranknowledge           Veteran Knowledge
glk:waxworx                    Wax Worx
glk:campwindylake              Camp Windy Lake
glk:woodsaredark               The Woods Are Dark
glk:worstgame                  The Worst Game In The World... Ever!!!
glk:wrecked                    Wrecked
glk:wumpusrun                  The Wumpus Run
glk:xycanthus                  Doomed Xycanthus
glk:yadfa                      Yet Another Damn Fantasy Adventure
glk:yonastoundingcastle        Yon Astounding Castle! of some sort
glk:advbackyard                An Adventurer's Backyard
glk:allthroughthenight         All Through the Night
glk:darkhour                   The Dark Hour
glk:jacarandajim               Jacaranda Jim
glk:jacd                       Just Another Christmas Day
glk:noblecrook1                Noble Crook, episode 1
glk:noblecrook2                Noble Crook, episode 2
glk:noblecrook3                Noble Crook, episode 3
glk:noblecrook4                Noble Crook, episode 4
glk:sonofcamelot               Son of Camelot
glk:ilgolem                    Il Golem
glk:3hgjailbreakbob            Jailbreak Bob
glk:3hgbriefcase               Briefcase
glk:3hgtheannihilationofthink  Annihilation of Think.com
glk:3hgshadricktravels         Shadrick's Travels
glk:3hglostsouls               Lost Souls
glk:3hgtheamulet               Amulet
glk:3hgzombiecow               Zombie Cow
glk:3hgsandl                   Snakes and Ladders
glk:3hgconfession              The Murder of Jack Morely
glk:3hgveteran                 Veteran Experience
glk:3hgburiedalive             Buried Alive
glk:3hgzac                     Zombies are Cool
glk:3hgtogetyou                We are coming to get you!
glk:goyshardsofmemory          Shards of Memory
glk:goypaint                   Paint!!!
glk:goydragonshrine            The Curse of DragonShrine
glk:goydarkness                Darkness
glk:aicmurdermansion           Murder Mansion
glk:aicoutline                 Outline
glk:aicsrs                     Silk Road Secrets: Samarkand to Lop Nor
glk:aicescape                  Must Escape!
glk:aicfinalquestion           The Final Question
glk:aicrift                    Rift
glk:aicp2p                     Point 2 Point
glk:aiczacksmackfoot           Zack Smackfoot
glk:amcthorn                   Thorn
glk:amcneighbours              Neighbours From Hell
glk:amcmonsters                Monsters
glk:amcdiarystrip              Diary of a Stripper
glk:1hgprincess1               The Princess In The Tower
glk:1hg1hrgame                 A Masochist's Heaven
glk:1hgendgame                 The Game To End All Games
glk:1hgchicken                 The Evil Chicken of Doom!
glk:1hghauntedhouse            The Haunted House of Hideous Horror
glk:1hgfrog                    The Green Princess
glk:1hgmicrobewillie           Microbe Willie vs. The Rat
glk:1hgjasonvssalm             Jason vs. Salm
glk:1hgpercy                   The Saga of Percy the Viking
glk:1hgforum                   Forum
glk:1hgdfu                     Dance Fever USA
glk:1hgforum2                  Forum 2
glk:1hgcrm                     That Crazy Radioactive Monkey!
glk:1hgasdfa                   A Short Damn Fantasy Adventure
glk:1hgdemonhunter             Apprentice of the Demonhunter
glk:1hgcbn1                    The Revenge of Clueless Bob Newbie!
glk:1hgcbn2                    The Revenge of Clueless Bob Newbie Part 2: This Time it's Personal
glk:1hgticktick                Doom Cat!!!
glk:1hgpyramid                 The Pyramid of Hamaratum
glk:1hgquesti                  Quest for Flesh
glk:1hgshore                   The Farthest Shore
glk:1hgsaffire                 Saffire
glk:1hgecod2                   The Curse of the Revenge of the Ghost of the Evil Chicken of Doom... Returns!
glk:1hgimagination             Just My Imagination-Musings of a Child
glk:1hgcah                     Cruel and Hilarious Punishment!
glk:1hgarghsgreatescape        Argh's Great Escape
glk:1hgshreddem                Shred 'em
glk:1hgagent4f                 Agent 4-F From Mars
glk:1hgecod3                   An Evening with the Evil Chicken of Doom
glk:1hgtrabula                 Get Treasure for Trabula
glk:1hgwoof                    Woof
glk:1hgundefined               Undefined
glk:1hgadriftmaze              Adrift Maze
glk:1hgicecream                Ice Cream
glk:1hgwreckage                SE: Wreckage
glk:1hgspam                    SPAM
glk:1hgvagabond                Vagabond
glk:1hgthecatinthetree         The Cat in the Tree
glk:1hgtopaz                   Topaz
glk:1hggoblinhunt              Goblin Hunt
glk:chooseyourown              Choose Your Own...
glk:darkhavenmystery           The Mystery Of The Darkhaven Caves
glk:shadricksunderground       Shadrack's Underground Adventure
glk:tickettonowhere            Ticket to No Where
glk:tearsofatoughman           Tears of a tough man
glk:theadriftproject           The ADRIFT Project
glk:iadcseaside                A Day At The Seaside
glk:iadcfrustrated             Frustrated Interviewee
glk:iadchub                    The House Husband
glk:iadcprivateeye             Private Eye
glk:iadcblood                  Fire in the Blood
glk:ahc3minutes                3 Minutes to Live
glk:1hgamonkeytoomany          A Monkey too many
glk:axeofkolt                  The Axe of Kolt
glk:castlecoris                The Spectre of Castle Coris
glk:cybercow                   Lair of the Cybercrow
glk:fistoffire                 Die Feuerfaust - The Fist of Fire
glk:hangover                   Hangover
glk:jaft                       Just Another Fairy Tale
glk:magneticmoon               Magnetic Moon
glk:mystman                    Mystman
glk:rtc                        Return to Camelot
glk:rtcc                       Return to Castle Coris
glk:sixsilverbullets           Six Silver Bullets
glk:spacedetective1            Space Detective, episode 1
glk:spacedetective2            Space Detective, episode 2
glk:spacedetective3            Space Detective, episode 3
glk:spacedetective4            Space Detective, episode 4
glk:spacedetective5            Space Detective, episode 5
glk:spacedetective6            Space Detective, episode 6
glk:spacedetective7            Space Detective, episode 7
glk:starshipquest              Starship Quest
glk:tcom1                      The Cave of Morpheus 1
glk:tcom2                      The Cave of Morpheus 2
glk:thetest                    The Test
glk:tingalan                   Tingalan
glk:advsys                     AdvSys Game
glk:bustedadvsys               Busted!
glk:starshipcolumbus           Starship Columbus
glk:elves87                    Elves '87
glk:keytotime                  The Key to Time
glk:onehand                    The Sound of One Hand Clapping
glk:pirating                   Pirating
glk:abloodylife                A Bloody Life
glk:alandria                   The Search for Princess Alandria
glk:alchemistcastle            Castle of the Alchemists
glk:advalice                   The Adventures of Alice Who Went Through the Looking-Glass
glk:apprenticetesting          Apprentice - The Testing of a Magical Novice
glk:sirarthur                  Sir Arthur
glk:cercla                     Cercla
glk:cardigan1                  Space Aliens Laughed at My Cardigan
glk:cardigan2                  Still Laughing at my Cardigan
glk:curse                      Curse of ManorLand
glk:sanityclause               Sanity Clause or, Why Santa Didn't Make It to YOUR House that Year
glk:cliffdiver1                Cliff Diver: Investigator for Hire - Case 1
glk:cliffdiver2                Cliff Diver: Investigator for Hire - Case 2
glk:cosmoserve                 CosmoServe
glk:crusade                    Crusade
glk:agtdetective               Detective
glk:dragonschocolate           Dragons in Chocolate Land
glk:disenchanted               Disenchanted
glk:ducksoup                   Duck Soup
glk:cavesofdyanty              Caves of Dyanty
glk:destinationearth           Destination: Earth
glk:dudleydilemma              A Dudley Dilemma
glk:80days                     Around the World in Eighty Days
glk:easteregghunt              Heather's Easter Egg Hunt
glk:electrabot                 Electrabot
glk:elf20                      The Elf's Christmas Adventure
glk:elfquest                   Elf Quest
glk:eliescape                  Escape from the ELI
glk:emailbox                   E-MAILBOX
glk:escapeprisonisland         Escape from Prison Island
glk:agtfable                   A Fable
glk:firststupidgame            My First Stupid Game
glk:ccfirstadv                 Colossal Cave - The First Adventure
glk:ggollek                    Ggollek I : The Dissolution
glk:agtghosttown               Ghost Town
glk:giganticsecrets            Secrets of the Gigantic
glk:newenglandgothic           New England Gothic
glk:grailmisadventure          The Misadventure of the Holy Grail
glk:hardestadv                 The World's Hardest Adventure
glk:helvera                    Helvera, Mistress of the Park
glk:highe                      Highe, the Adventures of Elizabeth("El") Highe
glk:sirramichobbs              Sir Ramic Hobbs and the High Level Gorilla
glk:holmescasebook             The Casebook of Sherlock Holmes
glk:hotelnotell                Hotel Notell
glk:house2house                House 2 House
glk:agthugecave                Adventure in Humongous Cave
glk:hurryhurry                 Hurry!Hurry!Hurry!!
glk:jackofhartz                Jack of Hartz
glk:jubileeroad                Jubilee Road
glk:killjustin                 Kill Justin
glk:klaustrophobia1            Klaustrophobia - Part I
glk:klaustrophobia2            Klaustrophobia - Part II
glk:klaustrophobia3            Klaustrophobia - Part III
glk:klingonrpg                 In the Year 2366, Klingon Role Playing Game
glk:deadlylabyrinth            The Deadly Labyrinth
glk:library                    Library - Library of Guilford College
glk:lostgold                   Lost Gold
glk:lostinspace                Lost in Space : Dr.Smith Goes Home
glk:agtlottery                 Lottery
glk:loststonemansion           Lost Stone Mansion
glk:agtpyramids                The Pyramids of Mars
glk:mdthief                    The Multi-Dimensional Thief
glk:agtmhpquest                Quest for the Magic Healing Plant
glk:mopandmurder               Mop and Murder
glk:agtmst3k1                  Detective, An Interactive MiSTing (Mystery Science Theater 3000)
glk:agtmst3k2                  Mystery Science Theater 3000, Adventure 102
glk:spacemule                  Space Mule
glk:myopia                     Myopia
glk:nmr1                       Adventures in NMR
glk:nmr2                       Adventures in NMR II : The Adventure Continues
glk:oceana                     Oceana
glk:agtodieus                  Odieus's Quest for the Magic Flingshot
glk:oklib                      Oklib's Revenge
glk:ovanpelt                   Orientation to Van Pelt Library of the University of Pennsylvania
glk:peterpatzer                The Adventures of Peter Patzer
glk:blackpearl                 Quest for the Black Pearl
glk:battleofphilip             The Battle of Philip against the Forces of Creation
glk:flightintofantasy          The Pilot or A Flight into Fantasy
glk:pork1                      PORK I : The Great Underground Sewer System
glk:pork2                      PORK II, The Gizzard of Showbiz
glk:starportal                 The Star Portal
glk:pastoralpitfalls           Pastoral Pitfalls
glk:lostproperty               Lost Property
glk:gameofrecovery             The Game of Recovery
glk:rerunsagain                Reruns Again version
glk:derring                    Der Ring des Nibelungen
glk:sherwoodadv                Adventures in Sherwood
glk:shapeshifteradv            Shape Shifter Adventure!
glk:sirguygallant              Sir Guy Gallant and the Deadly Warning
glk:shadesofgray               Shades of Gray
glk:sonofstagefright           Son of Stagefright
glk:spatent                    The Spatent Obstruction
glk:squynchia                  The Squynchia Adventure
glk:agtstiffy                  The Incredible Erotic Adventures of Stiffy Makane!
glk:storms1                    Storms I
glk:susan                      Susan (A Lustful Game)
glk:tamoret                    Tamoret
glk:tarabithia                 Escape from Tarabithia
glk:tarksimmons                The Adventure of Tark Simmons
glk:tarotia                    The Books of Tarotia : Book 1
glk:tempest                    The Tempest
glk:thegame                    Whatever We Decide To Call This Game
glk:therift                    The Rift
glk:tja                        The Jeweled Arena
glk:toho                       Toho Academy
glk:tossedintospace            Tossed into Space : Dr.Schmidt Goes Home
glk:timesquared                TimeSquared
glk:folkestone                 Murder at the Folkestone Inn
glk:void                       VOID:CORPORATION
glk:wanderer1                  Black Wanderer 1 - The Darkest Road
glk:wanderer2                  Black Wanderer 2 - The Unborn One
glk:wanderer3                  Black Wanderer 3 - Twas a Time of Dread
glk:weekendsurvival            Weekend Survival
glk:witchfinder                Witchfinder
glk:agtwizardscastle           The Wizard's Castle
glk:hobbswok                   Sir Ramic Hobbs and the Oriental Wok
glk:wraithblaster              Wraith Blaster
glk:journeyintoxanth           A Journey into Xanth
glk:zanfar                     Zanfar
glk:querido                    Querido
glk:alan2                      Alan2 Game
glk:bugged                     Bugged
glk:cc                         CC
glk:chasing                    The Chasing
glk:closet                     Closet
glk:dinnertime                 Dinnertime
glk:hebgb                      The HeBGB Horror!
glk:arthursnightout            King Arthur's Night Out
glk:lostinnewyork              Lost In New York
glk:mazemapper                 Mazemapper
glk:meanstory                  The Mean Story
glk:outofthestudy              Out Of The Study
glk:plsghints                  Painless Little Stupid Games Hints
glk:sardoria                   Sardoria
glk:presidentadventures        The Adventures of the President of the United States
glk:thechasing                 The Chasing
glk:afteryou                   They're After You
glk:tgttos                     To Get To The Other Side
glk:zeroone                    Zero One
glk:alan3                      Alan3 Game
glk:christmasparty             The Christmas Party
glk:deadleaves                 City of Dead Leaves
glk:enterthedark               Enter The Dark
glk:fishmess                   Fish Mess
glk:forbidden                  The Ngah Angah School of Forbidden Wisdom
glk:hwmurders                  Hollywood Murders
glk:misguided                  Mis/Guided
glk:room206                    Room 206
glk:tedpaladin                 Ted Paladin And The Case Of The Abandoned House
glk:thesealedroom              The Sealed Room
glk:waldospie                  Waldo's Pie
glk:wyldkyndproject            The Wyldkynd Project
glk:archetype                  Archetype IF Game
glk:guesstheanimal             Guess the Animal
glk:gorreven                   The Gorreven Papers
glk:starshipsolitaire          The Starship Solitaire adventure
glk:transylvania               Transylvania
glk:crimsoncrown               Crimson Crown
glk:ootopos                    OO-Topos
glk:transylvaniav2             Transylvania (V2)
glk:talisman                   Talisman: Challenging the Sands of Time
glk:glulx                      Glulx Game
glk:aafn                       An Apple From Nowhere
glk:abca                       A Beauty Cold and Austere
glk:academicpursuits           Academic Pursuits As Opposed To Regular Pursuits
glk:acbs                       A Cock and Bull Story
glk:acg                        Adventurer's Consumer Guide
glk:adventglulx                Adventure
glk:adventura                  Adventura
glk:airport                    The Airport
glk:alabaster                  Alabaster
glk:aliasthemagpie             Alias 'The Magpie'
glk:alone                      Alone
glk:alongdrink                 A Long Drink
glk:anatidaephobia             A N A T I D A E P H O B I A
glk:anchorheaddemo             Anchorhead: Special Edition Demo
glk:andromeda1983              Andromeda 1983
glk:andromedaapocalypseext     Andromeda Apocalypse (Extended Edition)
glk:andromedaascending         Andromeda Ascending
glk:andromedaawakening         Andromeda Awakening - The Final Cut
glk:andromedadream             Andromeda Dreaming
glk:ariadneinaeaea             Ariadne in Aeaea
glk:aroilingoriginal           A Roiling Original: Squeeal! A Sequel!
glk:aropeofchalk               A Rope of Chalk
glk:artoffugue                 Art of Fugue
glk:ascensionlimbs             Ascension of Limbs
glk:ascentgothictower          The Ascent of the Gothic Tower
glk:atc                        ATC, an interactive aviation
glk:aurora                     Aurora
glk:balancesglulx              Balances
glk:baretegi                   Baretegi
glk:barroombrawl               Barroom Brawl: Punch for your life
glk:beasttorrackmoor           The Beast of Torrack Moor
glk:beautyaustere              A Beauty Cold and Austere
glk:becauseyouremine           Because You're Mine
glk:beingthere                 Being There
glk:blindhouse                 The Blind House
glk:bluelacuna                 Blue Lacuna
glk:bonehead                   Bonehead, a Regrettable and Mostly True Tale
glk:brainguzzlers              Brain Guzzlers from Beyond!
glk:briar                      Briar, a Grimmly Perverted Fairy Tale
glk:btyt                       Bigger Than You Think
glk:bullhockey                 Bullhockey!
glk:bullhockey2                Bullhockey 2 - The Return of the Leather Whip
glk:bureaucrocyglulx           Bureaucrocy, a boring tale about paperwork
glk:buygold                    Buy Gold
glk:calm                       Calm, a Game of Postapocalyptic Relaxation
glk:candlewindless             Candle flames in windless air
glk:canyouescape               Can You Escape
glk:castronegroblues           Castronegro Blues
glk:caveglulx                  Cave
glk:cheesedoffglulx            Cheesed Off! A very cheesey adventure
glk:chipmonk                   Chipmonk
glk:chlorophyll                Chlorophyll
glk:codetopia                  Codetopia - A Code Adventure
glk:colderlight                The Colder Light: A Winter's Tale
glk:colorthetruth              Color the Truth
glk:comp01tr                   Comp01ter Game: N0n C0mp0s Ment1s
glk:confhist                   Conflicting Histories
glk:cos                        City of Secrets
glk:counterfeitmonkey          Counterfeit Monkey
glk:countingcrabs              Counting Crabs: How many crabs can you count?
glk:crackcoldone               Crack open a cold one with the Boiz
glk:cragne                     Cragne Manor
glk:damesdeadites              Dames and Deadites
glk:dansenocturne              Danse Nocturne
glk:darkcarnival               Dark Carnival
glk:darknessglulx              Darkness
glk:deadcities                 Dead Cities
glk:deathoffthecuff            Death Off the Cuff
glk:delphinashouse             Delphina's House
glk:desolation                 Desolation
glk:diaperquest                Diaper Quest
glk:discovertheworld           Discover The World
glk:doctorm                    The Life (and Deaths) of Doctor M
glk:donotmeddle                Do Not Meddle
glk:douchebag                  Douchebag, an Existential Adventure
glk:downtheserpent             Down, the Serpent and the Sun: an Anatomy
glk:dptmb2aa                   Don't Push The Mailbox 2 And Aisle
glk:dracula1glulx              Dracula: Part 1, The First Night
glk:dracula2glulx              Dracula: Part 2, The Arrival
glk:dragondemons               Dragon Demons: A World Traveling RPG
glk:dragonglulx                Dragon Adventure
glk:drolltolltroll             Droll Toll Troll
glk:dudewheresmyscapula        Dude, Where's My Scapula
glk:duelspannedages            The Duel that Spanned the Ages
glk:dungeonspuzzle             Dungeon's Puzzle
glk:dungeontext1               Dungeon Text I - Escape From Darkness
glk:eatme                      Eat Me
glk:elsegar1                   Elsegar I - Arrival
glk:endlesssands               Endless Sands
glk:endling                    The Endling Archive
glk:enterpriseincidents        The Enterprise Incidents: A Middle School Fantasy
glk:equivocalingredient        The Equivocal Ingredient
glk:fair                       Fair, an extra-curricular activity
glk:familiar                   The Familiar
glk:farmquest                  Farm Quest
glk:fatfair                    Fat Fair
glk:ferrousring                Ferrous Ring
glk:ferrymansgate              Ferryman's Gate
glk:finalproject               Final Project
glk:flattenedlondon            Flattened London
glk:flexiblesurvival           Flexible Survival
glk:followingastar             The Bible Retold: Following A Star
glk:foraplace                  For a Place by the Putrid Sea
glk:further                    Further, a color-coded existential tangle
glk:gatewayferrets             Gateway of the Ferrets
glk:genesisquest               Genesis Quest, an interlude through stories
glk:getout                     Get Out!
glk:ghosteringtonnight         Ghosterington Night
glk:glkchess                   Glk Chess
glk:glkebook                   GlkeBook
glk:greenmountains             The Green Mountains
glk:groovebillygoat            Groove Billygoat
glk:hardpuzzle1                Hard Puzzle
glk:hardpuzzle2                Hard Puzzle 2: The Cow
glk:hardpuzzle3                Hard Puzzle 3: Origins
glk:haroldnight2003            Harold Night 2003
glk:herecomestreble            Here Comes Treble
glk:hobbitglulx                The Hobbit - The True Story
glk:hobbitredux                The Hobbit - The True Story - Redux, Director's Cut
glk:houseofmemories            House of Memories
glk:houseofmystery             The House of Mystery
glk:hungerdaemon               Hunger Daemon
glk:illum                      Illuminismo Iniziato, an Interactive Illumination
glk:illwind                    Ill Wind, Yet Another Interactive Enigma
glk:immunesystem               Immune System
glk:ingoodcompany              In Good Company
glk:jasonandmedea              Jason and Medea
glk:kerkerkruip                Kerkerkruip
glk:killerheadache             A Killer Headache
glk:kingshredspatches          The King of Shreds and Patches
glk:klaustrophobia             Klaustrophobia
glk:koa                        Kingdom of Amphibia
glk:lasthouse                  Last House on the Block
glk:lastresort                 Last Resort, a sweltering afternoon in the Deep South
glk:limeergot                  Lime Ergot
glk:lmstvgglulx                LMS The Video Game
glk:lockdown                   Lockdown: a story of insanity, denial and death
glk:lockkey                    Lock and Key
glk:lostislandsofalabaz        The Lost Islands of Alabaz
glk:lovelyassistant            Lovely Assistant Magical Girl
glk:madametime                 The Origin of Madame Time
glk:makechangeglulx            Maybe make some change
glk:mgaeb                      My Girlfriend's An Evil Bitch
glk:mollybutterthieves         Molly and the Butter Thieves
glk:moments1                   Moments out of Time: Renegade
glk:moments2                   Moments out of Time 2: Adventure Type
glk:monksea                    Monk by the Sea
glk:moonbaseindigo             Moonbase Indigo
glk:mugglestudies              Muggle Studies
glk:mystery                    Mystery!
glk:narco                      Narcolepsy
glk:necronskeep                Necron's Keep
glk:newcat                     New Cat
glk:nightmare                  Nightmare
glk:nssri                      No Sign Should Remain Inert
glk:officegoose                Office Goose
glk:oldfogey                   Old Fogey
glk:oliviasorphanorium         Olivia's Orphanorium
glk:oppositelyopal             Oppositely Opal
glk:ottumwaglulx               PDFA Ottumwa
glk:owlconsults                The Owl Consults
glk:phoenixfire                Phoenix-Fire
glk:photopiaglulx              Photopia
glk:piedaterreblunders         Captain Piedaterre's Blunders
glk:pinched                    Pinched
glk:pizzadelivery              Pizza Delivery
glk:playinggames               Playing Games
glk:portfoliopiece             Portfolio Piece
glk:psychomanteum              Psychomanteum
glk:pythoglulx                 Pytho's Mask
glk:rar                        Reference and Representation: An Approach to First-Order Semantics
glk:reorsbushcaveglulx         Reor's Bush-Cave
glk:risorgglulx                Risorgimento Represso
glk:robinandorchid             Robin & Orchid
glk:rocketmanfromsea           The Rocket Man from the Sea
glk:roguelikegoose             Roguelike Goose
glk:rosewood                   The House at the End of Rosewood Street
glk:rover                      Rover's Day Out
glk:safe                       Safe
glk:sagebrushcactus            'Mid the sagebrush and the cactus
glk:sagesanctumscramble        Sage Sanctum Scramble
glk:samfortunepi               Sam Fortune - Private Investigator
glk:scrollthief                Scroll Thief, an Interactive Heist
glk:seasonalapocalypse         Seasonal Apocalypse Disorder
glk:secretletter               Jack Toresal and the Secret Letter
glk:section1awakened           Section 1 - Awakened
glk:sensory                    Sensory Jam
glk:sequitur                   Sequitur
glk:shadowcathedral            The Shadow in the Cathedral
glk:shadowoperative            Shadow Operative
glk:shapes                     Shapes: an Interactive Surrealism
glk:sheephere                  Sheep Here
glk:shufflingaround            Shuffling Around
glk:signalerror                Signal Error: Tongue-in-cheek glitch correction
glk:sittm                      Stick It To The Man
glk:six                        Six
glk:skmmc                      Someone Keeps Moving My Chair
glk:slouchingbedlamglulx       Slouching Towards Bedlam
glk:smittenkittens             Smitten Kittens
glk:spaceship                  Spaceship!
glk:speedracer                 Speed Racer
glk:spellbound                 Spellbound
glk:spirI7wrak                 SpirI7wrak
glk:standingshoulders          Standing on the Shoulders of Giants
glk:starlight                  Starlight
glk:stiffymakane               Stiffy Makane - Apocolocyntosis
glk:stuffoflegend              Stuff of Legend
glk:subrosa                    Sub Rosa: The Seven Deceits of Confessor Destine
glk:superluminalvagranttwin    Superluminal Vagrant Twin
glk:tcom                       The Colour of Magic
glk:templeshorgil              The Temple of Shorgil
glk:terminatorchaser           Terminator Chaser
glk:terminatorrobotrescue      Terminator, a Robot Rescue
glk:theabbey                   The Abbey, a medieval murder mystery
glk:theabsenceoflaw            The Absence of Law
glk:thebox                     The Box
glk:theeleusinianmiseries      The Eleusinian Miseries
glk:thefourthriddle            The Fourth Riddle
glk:thehours                   The Hours
glk:thehouseoffear             The House of Fear, or, Loplop Introduces the World
glk:theinformal7abbreviated    The Inform(al)7 Abbreviated Self Tutorial
glk:theislandofdoctorwooby     The Island of Doctor Wooby
glk:thelaughinggnome           The Laughing Gnome
glk:thelibrary                 The Library
glk:thelostkingdomofcodetopia  The Lost Kingdom of Codetopia
glk:themagpietakesthetrain     The Magpie Takes the Train
glk:themaryjaneoftomorrow      The Mary Jane of Tomorrow
glk:themuseum                  The Museum
glk:theoutcasts                The Outcasts
glk:thephoenixmove             The Phoenix Move
glk:therealmofaoria            The Realm of A'oria
glk:thesimpletale              The Simple Tale
glk:theskycrane                The Sky Crane
glk:thespywhoatelunch          The Spy Who Ate Lunch
glk:thestorm                   The Storm, a self-portrait
glk:thethiefofwovenwoods       The Thief of Woven Woods
glk:thetinyhouse               The Tiny House
glk:thetraintoabaddon          The Train To Abaddon
glk:thewaywardstory            The Wayward Story
glk:thiefpokemon               Thief, a Pokemon Text Adventure
glk:timeless                   Timeless
glk:todayisthesame             Today is the Same as Any Other
glk:tohellinahamper            To Hell in a Hamper
glk:tomtrundle                 The Incredibly Mild Misadventures of Tom Trundle
glk:transparent                Transparent, an interactive exploration
glk:trialofthetnuop            Trial of the Inuop
glk:trollslayer                Trollslayer
glk:tryagain                   Try Again 
glk:turbochesthair             Turbo Chest Hair Massacre
glk:uglyoafs                   Ugly Oafs. Save Green Terra! Repel the Wrath Pulse!
glk:uie                        Under, In Erebus
glk:umwglulx                   UMW
glk:uncleclemswill             Uncle Clem's Will
glk:underground                Underground
glk:undertheythunder           Under They Thunder
glk:unscientificfiction        Unscientific Fiction
glk:vainempires                Vain Empires
glk:valleyofsteel              Valley of Steel
glk:vampireltd                 Vampire Ltd
glk:walking                    Walking
glk:wand                       The Wand
glk:winterstormdraco           Winter Storm Draco
glk:wishertheurgist            Wisher, Theurgist, Fatalist
glk:wizardsniffer              The Wizard Sniffer
glk:wof                        Works of Fiction
glk:wordoftheday               Word of the Day
glk:wordsofpower               Words of Power
glk:zeldata                    The Legend of Zelda: A Text Adventure
glk:zorkglulx                  Zork: A Computerized Fantasy Simulation Game
glk:apollo3glulx               She's Actual Size
glk:apollo10glulx              Narrow Your Eyes
glk:apollo12glulx              Which Describes How You're Feeling
glk:apollo15glulx              Turn Around
glk:apollo19glulx              Fingertips - I Hear the Wind Blow
glk:apollo33glulx              Fingertips - Mysterious Whispers
glk:bestof3                    Best of three
glk:carma                      Carma
glk:smtuc                      Stiffy Makane: The Undiscovered Country
glk:eas2                       Earth and Sky: Episode 2 - Another Earth, Another Sky
glk:eas3                       Earth and Sky: Episode 3 - Luminous Horizon
glk:beyondglulx                Beyond
glk:cheiron                    Cheiron
glk:floatpoint                 Float Point
glk:chineseroom                The Chinese Room
glk:varkana                    Varkana
glk:amo                        A Martian Odyssey
glk:chnlsurf                   Channel Surfing
glk:crywolf                    Cry Wolf
glk:everybodydies              Everybody Dies, an Interactive Fantasy
glk:recess                     Recess At Last
glk:brokenlegs                 Broken Legs
glk:earlgrey                   Earl Grey
glk:gis                        Grounded in Space
glk:nightfall                  Nightfall
glk:resonance                  Resonance
glk:aotearoa                   Aotearoa
glk:divismortis                Divis Mortis: an interactive survival game
glk:gigantomania               Gigantomania
glk:grisjaune                  Gris et Jaune
glk:oneeyeopen                 One Eye Open
glk:oxygen                     Oxygen
glk:inerebus                   Under, In Erebus
glk:awakemightydread           Awake the Mighty Dread
glk:beet                       Beet the Devil
glk:deathofschlig              Death of Schlig
glk:faninterference            Fan Interference
glk:luster                     Luster
glk:patanoir                   PataNoir
glk:sentencing                 Sentencing Mr. Liddell
glk:tacofiction                Taco Fiction
glk:andromedaapoc              Andromeda Apocalypse
glk:imos                       In a Manor of Speaking
glk:jdal                       J'dal
glk:kicker                     Kicker
glk:awbp                       A Wind Blown from Paradise
glk:captverdeterre             Captain Verdeterre's Plunder
glk:coloratura                 Coloratura
glk:mazredugin                 Mazredugin
glk:ooof                       Ollie Ollie Oxen Free
glk:robinorchid                Robin & Orchid
glk:texbonaventure             Tex Bonaventure and the Temple
glk:cardewhouse                The Cardew House
glk:ekphrasis                  Ekphrasis, les Aventures de Gilbert Fontenelle
glk:lieuxcommunsglulx          Lieux communs
glk:sarvegneglulx              Sarvegne, une visite qui conduit loin
glk:scarabeekatana             Le Scarabee et le Katana
glk:templefeu                  Le Temple de Feu
glk:dergarten                  Der onirische Garten
glk:deronirischegarten         Der Garten: Der Aufenthalt in einem traumhaften Garten
glk:kleinehalbling             Der kleine Halbling
glk:matthiasclaudius           Der unsägliche und vermeidbare Tod des Matthias Claudius
glk:morgenwirdklausur          Morgen wird Klausur geschrieben
glk:patanoirde                 PataNoir - Ein unvergleichlicher Kriminalfall
glk:spaterbesuch               Ein später Besuch
glk:pietradellaluna            La Pietra della Luna
glk:mancasolo                  Manca solo un verso a quella poesia
glk:schizo                     Schizo - Escape to the Void
glk:slendermanbase             Slenderman - l'incubo (base)
glk:slenderman                 Slenderman - l'incubo
glk:snuff                      Snuff Movie
glk:villamorganaglulx          Villa Morgana
glk:alienlaaventura            ALIEN: La Aventura
glk:conrumbo                   Con Rumbo
glk:elultimohogarglulx         Misterio en el Ultimo Hogar
glk:hhorcusglulx               Homo Homini Orcus
glk:kerulenglulx               Ke rulen los petas
glk:lanochedelensayo           La Noche del Ensayo
glk:legado                     El Legado
glk:regente                    El Anillo Regente
glk:rur                        Las Aventuras de Rudolphine Rur
glk:drakmagiglulx              Drakmagi (Dragon Magic)
glk:vanyarglulx                Vanyar
glk:hugo                       Hugo IF Game
glk:acs                        A Crimson Spring
glk:annoyotron2                Aggravatron: Annoyotron II
glk:cb2                        The Clockwork Boy 2
glk:cryptozookeeper            Cryptozookeeper
glk:hugoclock                  The Hugo Clock
glk:adv350h                    Adventure, 350 point Colossal Cave
glk:distress                   Distress
glk:down                       Down
glk:dragonhunt                 Dragon Hunt
glk:eastofeastwood             East of Eastwood
glk:fallacyofdawn              Fallacy of Dawn
glk:futureboy                  Future Boy!
glk:guiltybastards             Guilty Bastards
glk:halloweenhorror1           The Halloween Horror - part 1
glk:halloweenhorror2           The Halloween Horror - part 2
glk:hammurabi                  Hammurabi
glk:htgessay                   Hauning the Ghosts
glk:hugozork                   Hugo Zork 1
glk:ish                        Escape from Ice Station Hippo
glk:ndrift                     Necrotic Drift
glk:nextday                    The Next Day
glk:nmnl                       Nothing More, Nothing Less
glk:partyarty                  Party Arty, Man of La Munchies
glk:paxless                    PAXLess, Quest to the IF Suite
glk:pirateadv                  Pirate Adventure
glk:pantomime                  Pantomime
glk:pom                        Persistence of Memory
glk:renga                      Renga in Four Parts
glk:retronemesis               Retro-Nemesis
glk:scavhunt                   Scavenger Hunt
glk:spinning                   Spinning
glk:spur                       Spur, A Western Misadventure
glk:squest                     SceptreQuest
glk:teleporttest               Teleport Test
glk:tetrish                    Tetris
glk:tradingpunches             Trading Punches
glk:travellingswordsman        Tales of the Travelling Swordsman
glk:tripkey                    Tripkey
glk:wfte                       Waiting for The End
glk:worldbuilder               Word Builder
glk:eldor                      The Curse of Eldor
glk:prisonbreak                Prisoner Break
glk:unholygrail                The Unholy Grail
glk:adrianmole1                Adrian Mole I
glk:adrianmole2                Adrian Mole II
glk:thearchers                 The Archers
glk:adventurequest             Adventure Quest
glk:colossaladvjod             Colossal Adventure /JoD
glk:dungeonadv                 Dungeon Adventure
glk:dungeonadvjod              Dungeon Adventure /JoD
glk:emeraldisle                Emerald Isle
glk:eriktheviking              Erik the Viking
glk:gnomeranger                Gnome Ranger
glk:ingridsback                Ingrid's Back
glk:knightorc                  Knight Orc
glk:lancelot                   Lancelot
glk:lordsoftime                Lords of Time
glk:lordsoftimetmgd            Lords of Time /T&M GD
glk:lordsoftimetm              Lords of Time /T&M
glk:priceofmagik               Price of Magik
glk:priceofmagiktmgd           Price of Magik /T&M GD
glk:priceofmagiktm             Price of Magik /T&M
glk:redmoon                    Red Moon
glk:redmoontmgd                Red Moon /T&M GD
glk:redmoontm                  Red Moon /T&M
glk:returntoeden               Return to Eden
glk:returntoedensd             Return to Eden /SD
glk:scapeghost                 Scapeghost
glk:snowball                   Snowball
glk:snowballsd                 Snowball /SD
glk:worminparadise             Worm in Paradise
glk:worminparadisesd           Worm in Paradise /SD
glk:magnetic                   Magnetic Scrolls Game
glk:corruption                 Corruption
glk:fish                       Fish!
glk:guild                      The Guild of Thieves
glk:jinxter                    Jinxter
glk:myth                       Myth
glk:pawn                       The Pawn
glk:wonderland                 Wonderland
glk:quest                      Quest Game
glk:adventureq                 Adventure!
glk:attemptedassassination     Attempted Assassination
glk:beam                       Beam
glk:bladesentinel              The Blade Sentinel
glk:gatheredindarkness         Gathered in Darkness
glk:hauntedhorror              Haunted Horror
glk:lovesong                   Lovesong
glk:magicworld                 Magic World
glk:redsaucemonday             Red Sauce Monday
glk:worldsend                  World's End
glk:adventureland              Adventureland
glk:pirateadventure            Pirate Adventure
glk:missionimpossible          Mission Impossible
glk:voodoocastle               Voodoo Castle
glk:thecount                   The Count
glk:strangeodyssey             Strange Odyssey
glk:mysteryfunhouse            Mystery Fun House
glk:pyramidofdoom              Pyramid Of Doom
glk:ghosttown                  Ghost Town
glk:savageisland               Savage Island
glk:savageisland1              Savage Island, Part 1
glk:savageisland2              Savage Island, Part 2
glk:goldenvoyage               The Golden Voyage
glk:claymorguesorcerer         Sorcerer of Claymorgue Castle
glk:pirateisle                 Return to Pirate Isle
glk:buckaroobanzai             Buckaroo Banzai
glk:marveladventure            Marvel Adventure #1
glk:marveladventure2           Marvel Adventure #2
glk:scottsampler               Adventure International's Mini-Adventure Sampler
glk:robinofsherwood            Robin Of Sherwood
glk:goldenbaton                Mysterious Adventures 1: The Golden Baton
glk:timemachine                Mysterious Adventures 2: The Time Machine
glk:arrowofdeath1              Mysterious Adventures 3: Arrow of Death Part 1
glk:arrowofdeath2              Mysterious Adventures 4: Arrow of Death Part 2
glk:pulsar7                    Mysterious Adventures 5: Escape from Pulsar 7
glk:circus                     Mysterious Adventures 6: Circus
glk:feasibility                Mysterious Adventures 7: Feasibility Experiment
glk:akyrz                      Mysterious Adventures 8: The Wizard of Akyrz
glk:perseus                    Mysterious Adventures 9: Perseus and Andromeda
glk:10indians                  Mysterious Adventures 10: Ten Little Indians
glk:waxworks11                 Mysterious Adventures 11: Waxworks
glk:mysadv1                    11 Mysterious Adventures - Disk 1
glk:mysadv2                    11 Mysterious Adventures - Disk 2
glk:desert                     Desert Adventure
glk:jamesbondadv               James Bond Adventure
glk:burglarsadv                Burglar's Adventure
glk:underseaconquest           Undersea Conquest part 1
glk:gammaworld                 Gamma World
glk:marooned                   Marooned
glk:minersadv                  Miner's Adventure
glk:romulanadv                 Romulan Adventure
glk:topsecretadv               Top Secret Adventure
glk:gremlins                   Gremlins
glk:seasofblood                Seas Of Blood
glk:supergran                  Super Gran
glk:amfv                       A Mind Forever Voyaging
glk:ballyhoo                   Ballyhoo
glk:beyondzork                 Beyond Zork
glk:borderzone                 Border Zone
glk:bureaucracy                Bureaucracy
glk:cutthroats                 Cutthroats
glk:deadline                   Deadline
glk:enchanter                  Enchanter
glk:hhgttg                     The Hitchhiker's Guide to the Galaxy
glk:hollywoodhijinx            Hollywood Hijinx
glk:infidel                    Infidel
glk:journey                    Journey
glk:lgop                       Leather Goddesses of Phobos
glk:infocomsampler1            Infocom Sampler 1
glk:infocomsampler2            Infocom Sampler 2
glk:lurkinghorror              The Lurking Horror
glk:milliways                  Milliways
glk:minizork1                  Mini Zork I: The Great Underground Empire
glk:moonmist                   Moonmist
glk:nordbert                   Nord and Bert Couldn't Make Head or Tail of It
glk:planetfall                 Planetfall
glk:plunderedhearts            Plundered Hearts
glk:questforexcalibur          Arthur: The Quest for Excalibur
glk:seastalker                 Seastalker
glk:sherlockriddle             Sherlock: The Riddle of the Crown Jewels
glk:shogun                     James Clavell's Shogun
glk:sorcerer                   Sorcerer
glk:spellbreaker               Spellbreaker
glk:starcross                  Starcross
glk:stationfall                Stationfall
glk:suspect                    Suspect
glk:suspended                  Suspended
glk:trinity                    Trinity
glk:wishbringer                Wishbringer
glk:thewitness                 The Witness
glk:zork0                      Zork Zero: The Revenge of Megaboz
glk:zork1                      Zork I: The Great Underground Empire
glk:zork2                      Zork II: The Wizard of Frobozz
glk:zork3                      Zork III: The Dungeon Master
glk:ztuu                       Zork: The Undiscovered Underground
glk:zcode                      Unknown Z-code game
glk:404life                    404 - Life not found
glk:69105keys                  69,105 Keys
glk:7doctors                   The Seven Doctors
glk:905                        9:05
glk:9dancers                   The Nine Dancers (Larsoft Adventure number 4)
glk:9lives                     9Lives
glk:aasmasters                 AAS Masters, in which all is revealed
glk:absoluteworstgame          The Absolute Worst IF Game in History
glk:accuse                     Accuse
glk:acheton                    Acheton
glk:acorncourt                 The Acorn Court
glk:acrobat                    The Mysterious Case of the Acrobat and His Peers
glk:acrossstars                Across the Stars
glk:acrossstarsclues           Across the Stars: Invisiclues
glk:acrossthestars             Across the Stars
glk:acrossthestarshints        Across the Stars: InvisiHints
glk:actofmurder                An Act of Murder
glk:addendum                   Flawed Addendum
glk:adoo                       ADOO'S STINKY STORY
glk:adv                        Adventure, Colossal Cave
glk:adv350                     Adventure, 350 point Colossal Cave
glk:adv440                     Adventure II, 440 point Colossal Cave
glk:adv550                     Adventure 3, 550 point Colossal Cave
glk:adv551                     Adventure 6, 551 point Colossal Cave
glk:adventurelobjan            Adventure (Lobjan translation)
glk:adventuretime              Adventure Time
glk:adverbum                   Ad Verbum
glk:advhoudini                 The Adventures of Houdini
glk:afflicted                  Afflicted
glk:affront                    Annoyotron IV: Affrontotron
glk:aisle                      Aisle
glk:alice                      Alice Through the Looking Glass
glk:allroads                   All Roads
glk:alongtheriver              Along the River
glk:alpha                      Journey to Alpha Centauri (In Real Time)
glk:ambassadorsdaughter        The Ambassador''s Daughter, a Brief Romance
glk:amish                      Amishville
glk:amiss                      Amissville
glk:anachronist                Anachronist
glk:anchor                     Anchorhead: an Interactive Tale of Lovecraftian Horror
glk:andrewplotkin              Being Andrew Plotkin
glk:andromedaawakeningz        Andromeda Awakening
glk:andromedagenesis           Andromeda Genesis
glk:anewlife                   A New Life
glk:animals                    Animals 1.1
glk:annoy                      Annoyotron
glk:anothergoddamnescape       Another Goddamn Escape the Locked Room Game
glk:aotyrz                     Attack of the Yeti Robot Zombies
glk:aphasiaquest               Aphasia Quest
glk:apocalypseclock            The Apocalypse Clock
glk:appall                     Appallatron: Annoyotron 3
glk:aridandpale                Arid and Pale
glk:asgard                     The 12:54 to Asgard
glk:asylum                     Asylum
glk:atomicheart                The Atomic Heart
glk:atrocitron                 Atrocitron, An Interactive Puzzlebox
glk:ats                        A Tight Spot
glk:atwork                     Danger! Adventurer At Work!
glk:aug4                       Augmented Fourth, an Interactive Performance
glk:avon                       Avon
glk:awakening                  The Awakening
glk:awitl                      A Week In The Life
glk:ayac                       Are You A Chef? An interactive ifMUD-saving
glk:b2demo                     Pick up the Phone Booth and Die, Part 2
glk:b7snare                    Snare, an interactive Blake's 7 adventure
glk:babytree                   Baby tree
glk:backtowakeup               Back to WakeUp, a Backpacker Tale
glk:backup                     Backup, an Interactive System Failure
glk:balances                   Balances, An Interactive Short Story
glk:baldersdeath               Balder's Death
glk:ballerina102               Not Just an Ordinary Ballerina
glk:balt24                     Baltimore:24, An Exercise in Interactive Fiction
glk:baluthar                   BALUTHAR
glk:bathtub                    There's a Snake in the Bathtub, a Test of Patience
glk:bazic                      baZic version 0.1, Z-Machine BASIC implementation
glk:beanstalker                The Bean Stalker
glk:bear                       A Bear's Night Out, an Interactive Children's Story
glk:bedlam                     Bedlam, An Interactive Preview
glk:bedtime                    Bed Time
glk:beingsteve                 Being Steve
glk:bellclap                   Bellclap
glk:bellwater                  Lord Bellwater's Secret
glk:beneath                    Beneath: a Transformation
glk:beneathatransformation     BENEATH: a Transformation
glk:betatester                 Beta Tester
glk:beyond                     Beyond
glk:bibleretold                The Bible Retold: The Bread and the Fishes
glk:bibleretoldbread           The Bible Retold: The Bread and the Fishes
glk:bibleretoldlostsheep       The Bible Retold: The Lost Sheep
glk:bicon                      BiCon, an Interactive Infatuation
glk:bigscoop                   The Big Scoop
glk:biscuit                    Biscuit, An Interactive Funeral
glk:bishoes                    Buried In Shoes
glk:bj                         Blow Job Drifter, An Interactive You Kno What
glk:blacklily                  The Black Lily
glk:blair                      Tales From The College Presents A Breath Of Fresh Blair
glk:blink                      Blink
glk:bloodless                  Bloodless on the Orient Express
glk:bluechairs                 Blue Chairs
glk:blues                      Tinseltown Blues: A quest for success in Hollyweird
glk:bluesky                    Blue Sky
glk:bodybargain                Body Bargain
glk:bofh                       The Bastard Operator from Hell
glk:bomber                     The Mad Bomber
glk:bookvol                    Book and Volume
glk:booth                      Pick up the Phone Booth and Die
glk:boothdye                   Pick up the Phone Booth and Dye
glk:brainnightguest            Brain of the Night Guest
glk:brandx                     BrandX
glk:breakin                    Break-In, an Interactive Burglary
glk:briantimmons               The Surprising Case of Brian Timmons
glk:bronze                     Bronze, Inform 7 demonstration game
glk:bryantcollection           The Bryant Collection, an Interactive Anthology
glk:bse                        BSE, An Interactive Epidemic
glk:buccaneerscache            Buccaneer's Cache
glk:building                   Building
glk:bureaucrocy                Bureaucrocy, a frustrating tale about paperwork
glk:burglar                    Burglar! A Learning Experience
glk:burnkoran                  Burn The Koran and Die
glk:burnsnightsupper           Burns Night Supper
glk:busted                     Busted! A game of high cunning and low humor
glk:byod                       BYOD
glk:byzantine                  Byzantine Perspective
glk:byzantineperspective       Byzantine Perspective
glk:cabal                      The Cabal: The Interactive Illuminati
glk:cacophony                  Cacophony, an interactive stumbling
glk:caffeination               Caffeination
glk:calendar                   Calendar, an Inform 7 abuse
glk:calmmutemoving             Calm, Mute, Moving
glk:calypso                    Calypso
glk:canamicah                  Cana According To Micah
glk:candy                      Candy, An Attempt at Reliving Childhood
glk:cars                       ASCII Cars!!! A game of racing with the imagination
glk:casting                    Casting
glk:castleadventure            Castle Adventure!
glk:castleredprince            Castle of the Red Prince, an interactive land of darkness
glk:catcherintherye            Catcher in the Rye
glk:catseye                    Cat's Eye, Miniventure #2
glk:causality                  Causality: The Search for Eternal Life
glk:caveadventure              Cave Adventure
glk:cavernofdoom               Zork: The Cavern of Doom
glk:cavernsofchaos             Caverns of Chaos
glk:cavetrip                   The Spelunking Trip
glk:ccake                      Arthur Yahtzee: The Curse of Hell's Cheesecake
glk:cdst                       Carmen Devine: Supernatural Troubleshooter
glk:cenricfamilycurse          The Cenric Family Curse
glk:changes                    Changes
glk:chaos                      Chaos
glk:chaosgame                  Chaos
glk:cheater                    Cheater, An Annoying Adventure
glk:cheesedoff                 Cheesed Off!
glk:cheeseshop                 Cheeseshop
glk:cheshirecat                Save the Cheshire Cat!
glk:chico                      Chico and I Ran
glk:childsplay                 Child's Play, A child, a toy, and a rival
glk:chix                       Chicks Dig Jerks
glk:christminster              Christminster
glk:chronicler0                The Chronicler
glk:cia                        CIA Adventure
glk:claw                       Wearing the Claw
glk:cleanair                   Clean Air
glk:cliffedge                  Edge of the Cliff
glk:cockandbull                A Cock and Bull Story
glk:codenamesilver             Code Name Silver Steel
glk:cointoss                   Coin toss
glk:coke                       Coke Is It!
glk:coldiron                   Cold Iron
glk:colonists                  Colonists
glk:coloromc                   Color of Milk Coffee
glk:colourpink                 The Colour Pink
glk:comedyerrormessages        A Comedy of Error Messages
glk:comp96                     Yearly IF competitions unofficial 'front-end' game
glk:conankill                  Conan Kill Everything
glk:conceptisproven            My Little Project Concept is Proven
glk:condemned                  Condemned
glk:constraints                Constraints
glk:cottage                    Cottage
glk:countdown1                 Countdown 1 - The Body
glk:countdown2                 Countdown 2 - The Soul
glk:countdown3                 Countdown 3 - The Mind
glk:cove                       The Cove
glk:crabhat                    Oh No, Mr Crab Stole Your Hat!
glk:creepydemo                 A Day in the Creepy Life of Bob Demo
glk:crimescene                 A Crime Scene, a Short Story
glk:criticalbreach             Critical Breach, an Escape Story
glk:crobe                      Crobe
glk:cryptographer              Cryptographer
glk:crystalpalace              The Crystal Palace
glk:csbb                       Crystal and Stone Beetle and Bone
glk:ctdoom                     Countdown to Doom
glk:cubicle                    In The Cubicle
glk:curses                     Curses, An Interactive Diversion
glk:curves                     Dangerous Curves
glk:cycles                     Vicious Cycles
glk:cyclops                    The Land of the Cyclops
glk:damnatiomemoriae           Damnatio Memoriae
glk:darkiss1                   Darkiss! Wrath of the Vampire - Chapter 1: The Awakening
glk:dashslapney                Dash Slapney, Patrol Leader
glk:dayinlife                  A Day in Life
glk:dayishothitler             The Day I Shot...
glk:dd4                        Dutch Dapper IV: The Final Voyage
glk:dday                       D-Day
glk:deadlineenchanter          Deadline Enchanter
glk:deadmansgrave              Dead Man's Grave: A Tell Don't Show Mystery
glk:deadmeat                   Dead Meat in the Pit
glk:deadpavane                 Dead Pavane for a Princess
glk:deadreckoning              Dead Reckoning
glk:deadsville                 Deadsville
glk:death                      Death to my Enemies
glk:deathoffthecuffz           Death Off The Cuff
glk:debate                     Debate
glk:deephome                   Deephome
glk:degeneracy                 Degeneracy
glk:dejavuz                    Deja Vu
glk:deliciousbreakfast         Delicious Breakfast
glk:delightfulwallpaper        Delightful Wallpaper
glk:delusions                  Delusions
glk:detective                  Detective
glk:detention                  Detention, an attempt to escape from school
glk:devildoit                  The Devil Made Me Do It
glk:devours                    All Things Devours
glk:dewdrops                   Within a Wreath of Dewdrops
glk:djinni                     The Djinni Chronicles "Undercurrents of Manipulation"
glk:doghouse                   The Dog/House
glk:dogslife                   It's a Dog's Life
glk:domicile                   Domicile
glk:dontgo                     Don't Go
glk:dontpeeyourself            Don't Pee Yourself!
glk:dontpushthemailbox         Don't Push The Mailbox
glk:dotd                       Dawn of the Demon
glk:downthematrix              Down The Matrix
glk:downtowntokyo              Downtown Tokyo Present Day
glk:dpod                       Dracula - Prince of Darkness
glk:dracula1                   Dracula: Part 1, The First Night
glk:dracula2                   Dracula: Part 2, The Arrival
glk:draculascrypt              Dracula's Underground Crypt
glk:dragon                     Dragon Adventure
glk:dragonflies                Dragon Flies Like Labradorite
glk:dragontroll                The Dragon and the Troll
glk:dreamcorruptor             Corrupter of Dreams
glk:dreamhold                  The Dreamhold
glk:dreamtooreal               A Dream Too Real
glk:drearylands                Dreary Lands
glk:drego                      Dr Ego and the egg of ManToomba
glk:dual                       Dual Transform
glk:duelinsnow                 The Duel in the Snow
glk:duelthatspanned            The Duel that Spanned the Ages
glk:dumont                     Dr. Dumont's Wild P.A.R.T.I
glk:eas                        Earth And Sky: Episode 1
glk:eastgrovehills             East Grove Hills
glk:edifice                    The Edifice
glk:eduardseminarist           Eduard the Seminarist
glk:egyptianwalking            Egyptian Walking Simulator
glk:elephants                  When I Was Shot By Elephants III
glk:eleven                     Film at Eleven
glk:eliza                      Eliza
glk:emptyroom                  The Empty Room
glk:enemies                    Enemies
glk:enigma                     Enimga
glk:entangled                  Entangled
glk:enterprise                 The Enterprise Incidents
glk:entropy                    Entropy
glk:epyk                       Eypk
glk:erden                      Travels in the Land of Erden: In Quest of the Adventure
glk:eric                       Eric The Power-Mad Dungeon Master
glk:eruption                   Eruption
glk:escapade                   Escapade!
glk:escape                     Escape!
glk:escaperemember             An Escape To Remember
glk:eurydice                   Eurydice
glk:f209                       Apartment 209
glk:fable                      A Fable
glk:faculty                    The Care and Feeding of Adjuncts
glk:failsafe                   FailSafe
glk:fairyland                  Fairyland
glk:farm                       The Farmer's Daughter
glk:fff                        Fox, Fowl and Feed
glk:figaro                     Figaro
glk:fightorflight              Fight or Flight
glk:figueres                   Figueres in my Basement
glk:finalselection             Final Selection
glk:findesick                  Fin de sickleburg
glk:findthebed                 Find the Bed
glk:finetuned                  Fine-Tuned
glk:fingertipsfriend           Fingertips: I Found a New Friend
glk:fingertipsmilk             Fingertips: Please Pass the Milk Please
glk:firstday                   The First Day of My New Life
glk:fishbowl                   Fish Bowl
glk:fmvpoker                   Frobozz Magic Video Poker
glk:forachange                 For a Change
glk:forestdemo                 Forest Demo
glk:forgottengirls             The Forgotten Girls
glk:fork                       Fork: The Great Underground Dining Room
glk:forms                      Of Forms Unknown
glk:foxfowl                    FOX, FOWL AND FEED
glk:fracture                   Fractured Metamorphoses (Example Version)
glk:fragileshells              Fragile Shells
glk:frankie                    Frankenstein Adventure
glk:freedom                    Freedom
glk:freefall                   Free Fall
glk:frobozzi                   The Encyclopedia Frobozzica (Abridged Edition)
glk:frozen                     Frozen: A Night at the Lab
glk:ftaegea                    Fort Aegea
glk:furtherz                   further
glk:futuregame                 FutureGame
glk:fyleet                     Fyleet
glk:ga                         Geocaching Adventure - GC3JJ9C - Cryptic Puzzle #6
glk:galatea                    Galatea
glk:gameproducer               Game Producer!
glk:gamer                      Gamer: Digital Limbo
glk:gamlet                     Gamlet
glk:gardening                  Gardening for Beginners
glk:garliccage                 The Garlic Cage, Episode I
glk:gatoron                    GATOR-ON, Friend to Wetlands!
glk:gaucho                     Gaucho
glk:gbvb                       Grandma Bethlinda's Variety Box
glk:gd                         Goodbye Doggy
glk:geb                        GOOSE, EGG, BADGER
glk:geist                      Geist
glk:gerbilriot                 Gerbil Riot
glk:ghost                      The Ghost Train
glk:ghostmountain              Ghost Mountain
glk:glass                      Glass, a fractured fairy tale
glk:gleamingtheverb            Gleaming the Verb
glk:glik1                      Glik part 1: Undead Menace
glk:gloriousrevolution         The People's Glorious Revolutionary Text Adventure Game
glk:gnuzoo                     Gnu in the Zoo
glk:godot                      Looking For Godot
glk:goldilocks                 Goldilocks is a Fox!
glk:golf                       Textfire Golf
glk:gostak                     The Gostak
glk:gourmet                    Gourmet
glk:gourmetgaffe               Gourmet Gaffe
glk:gowest                     Go West
glk:grandquest                 The Grand Quest
glk:greatpancake               The Great Pancake Detectives - Case #27
glk:greatxavio                 The Great Xavio
glk:greenrain                  A Green Rain
glk:grief                      Grief
glk:growingup                  Growing Up
glk:grue                       GRUE
glk:guard                      Guard Duty
glk:guess                      Guess The Verb!
glk:guestreet                  Life on Gue Street
glk:gumshoe                    Gumshoe
glk:gussdeath                  Guss's Death
glk:halloweve                  Hallow Eve
glk:hamhouse                   In the House of Professor Evil: The HAM HOUSE
glk:hamil                      Hamil
glk:hangar22                   Hangar 22
glk:happyeverafter             Happy Ever After
glk:hauntedhouse               Haunted House
glk:hauntings                  Hauntings
glk:heated                     Heated
glk:hedge                      Hedge
glk:heist                      Heist: The Crime of the Century
glk:heliopause                 Hoist Sail for the Heliopause and Home
glk:hell0                      Hell: A Comedy of Errors
glk:hellosword                 Hello Sword: The journey
glk:hellsbasement              Hell's Basement
glk:helpcollides               When Help Collides: The Wreck of the H.M.S. Snark
glk:henribeauchamp             The Gallery of Henri Beauchamp
glk:heroes                     Heroes
glk:heroinesmantle             Heroine's Mantle
glk:hiddennazi                 The Game Formerly Known as Hidden Nazi Mode
glk:hiddenverbiage             Hidden Verbiage
glk:hidepachyderm              Hide a pachyderm!
glk:hipponewyear               And A Hippo New Year
glk:historyrepeating           History Repeating
glk:hlainform                  HLA Inform: A Classic Quest
glk:hobbittruestory            The Hobbit - The True Story
glk:home                       Home
glk:homecoming                 Homecoming
glk:hoosegow                   Hoosegow, a Wild West Wreck
glk:horriblepyramid            The Horrible Pyramid
glk:house                      The House
glk:housedream                 House of Dream of Moon
glk:housekey1                  Housekey, Part I
glk:houseoffear                The House of Fear
glk:hummingbird                Flight of the Hummingbird
glk:humongouscave              Adventure in Humongous Cave
glk:humongouscavehints         Humongous Cave Hints
glk:hunterdark                 Hunter, in Darkness
glk:hyperrpg                   Hyper RPG Game!
glk:i0                         I-0: the "jailbait on the interstate" game
glk:ibo                        Ibo
glk:icebreaker                 Icebreaker
glk:iceprincess                The Ice Princess
glk:iceweb                     Iceweb
glk:identity                   Identity
glk:idthief                    IDENTITY THIEF
glk:ifaquarium                 IF Aquarium
glk:ifplayer                   Interactive Fiction Player
glk:ifquake                    Text adventure Quake Level 1
glk:ifwhispers5                IF Whispers 5
glk:ill                        I'll
glk:imiagination               Imiagination
glk:inamanor                   In a Manor of Speaking
glk:inevita                    Inevitable
glk:informatory                Informatory
glk:informschool               Inform School
glk:inhumane                   Inhumane: An Infralogic Massacre
glk:insidewoman                Inside Woman
glk:insight                    Insight
glk:intangible                 Intangible
glk:interface                  Interface
glk:internaldocuments          INTERNAL DOCUMENTS
glk:internalvigilance          Internal Vigilance
glk:interviewrockstar          Interview with a Rock Star
glk:intruder                   Intruder - Interactive Fiction: A Burglary
glk:invisibleadv               The Believable Adventures of an Invisible Man
glk:invisibleman               The Believable Adventures of an Invisible Man
glk:iraqiinvasion              Iraqi Invasion: A Text Misadventure
glk:island                     The Island
glk:islandsfaraway             Islands Far Away
glk:jackmills                  My Name is Jack Mills
glk:jane                       Jane
glk:janitor                    Janitor
glk:jetblue                    Jet-Blue
glk:jewelofknowledge           The Jewel of Knowledge
glk:jigsaw                     Jigsaw, An Interactive History
glk:jigsawrules                Jigsaw: Rules and Footnotes
glk:juicehead                  Juicehead, an interactive binge
glk:justanotherday             Just Another Day
glk:karn                       Return to Karn
glk:kazooist                   The Kazooist
glk:keepingdido                Keeping Dido
glk:keepsake                   Keepsake
glk:kentishplover              Kentish Plover
glk:kidnapsea                  Kidnapped - On the Sea
glk:kierkegaardsspider         Kierkegaard's Spider
glk:kiiwii                     Kii!Wii! A tiny friend to brighten your day
glk:killingthedoctor           Killing the Doctor
glk:kirby                      The X-Child, Kevin Johnson Residence Hall Saga 2
glk:kitten                     robotfindskitten
glk:koan                       KOAN
glk:kooku                      Kook U
glk:labyrinth                  Labyrinth
glk:lackofvision               Lack of Vision
glk:lambs                      Silence of the Lambs
glk:lambs2                     Silence of the Lambs 2
glk:lardo                      THE FAT LARDO AND THE RUBBER DUCKY
glk:largemachine               Large Machine
glk:lash                       Local Asynchronous Satellite Hookup
glk:lastdayofsummer            Last Day of Summer
glk:ldodoom                    Last Days of Doom
glk:leaptime                   Leap Time
glk:lecture                    Lecture Feature
glk:legion                     Legion
glk:lex                        LeX
glk:librarian                  Life of A Librarian
glk:libraryfront               All Quiet on the Library Front
glk:lifeordeath                Life or Death
glk:limp                       Limp
glk:lionskin                   In the Skin of a Lion Quest: Caravaggio's Journey
glk:lists                      Lists and Lists
glk:livejoseph                 LiveJoseph
glk:llr3                       A Little Like Rogue
glk:lmstvg                     LMS The Video Game
glk:lockeddoor1                Locked Door I
glk:lockeddoor2                Locked Door II
glk:lockeddoor3                Locked Door III
glk:lockeddoor4                Locked Door IV
glk:lockeddoor5                Locked Door V
glk:lockeddoor6                Locked Door VI
glk:lockeddoor7                Locked Door VII
glk:lockeddoor8                Locked Door VIII
glk:lockeddoor9                Locked Door IX
glk:lookingtothesky            Looking to the Sky
glk:lostpigandplace            Lost Pig And Place Under Ground
glk:lostpig                    Lost Pig
glk:lostsheep                  The Bible Retold: The Lost Sheep
glk:lostspellmaker             The Lost Spellmaker
glk:ludicorp                   The Ludicorp Mystery
glk:lunarbase1                 Lunar Base 1
glk:madamspider                Madam Spider's Web
glk:magicmuffin                Magic Muffin - The Desert
glk:magictoyshop               The Magic Toyshop
glk:makeitgood                 Make it Good
glk:manalive1                  MANALIVE I - ENIGMA
glk:manalive2                  MANALIVE II
glk:mansion                    Mansion
glk:martyquest                 Back to the Future - Marty Quest: an adventure through time
glk:masquerade                 Masquerade
glk:medusa                     Medusa, NPC Conversations Example
glk:mercurytrucking            The Mercury Trucking Company
glk:mercy                      Mercy
glk:metamorphoses              Metamorphoses
glk:mhpquest                   Quest for the Magic Healing Plant
glk:midpoints                  Midpoints
glk:mimesis                    Sins Against Mimesis
glk:mindelectric               The Mind Electric
glk:mines                      Mines
glk:mingsheng                  MingSheng
glk:minimalistgame             The Minimalist Game
glk:minionunderworld           Bobby T. Minion in "Escape from the Underworld"
glk:misdirection               The Act Of Misdirection
glk:missinggrandpa             Missing Grandpa: Lost in Time
glk:mite                       Mite
glk:mobius                     Möbius
glk:monstermaker               Monster Maker
glk:monzasphantom              Monza's Phantom
glk:moonglow                   Moonglow, Miniventure #1
glk:moonlittower               The Moonlit Tower
glk:moonshaped                 Moon-Shaped
glk:moonwrecked                Moonwrecked
glk:more                       More
glk:mortlakemanor              Mortlake Manor
glk:motherloose                Mother Loose
glk:mountain                   Mountain, an Interactive Expedition
glk:mousequest                 Mouse Quest Chapter 1 - The Arrival of Winter
glk:mrp                        The Story of Mr. P.
glk:mst3k1                     Detective, An Interactive MiSTing (Mystery Science Theater 3000)
glk:mst3k2                     A Fable, interactive MiSTing-up of "A Fable"
glk:muffinquest                The Quest for the Magic Muffin
glk:muffinquest3               Quest for the Magic Bagel...Err Muffin 3
glk:mulldoon                   The Mulldoon Legacy
glk:mulldoonmurders            The Mulldoon Murders
glk:murdac                     Murdac
glk:murderaeroclub             Murder at the Aero Club
glk:murdererleft               What The Murderer Had Left
glk:murphyslaw                 Murphy's Law
glk:muse                       Muse: An Autumn Romance
glk:musician                   The Musician
glk:myangel                    My Angel
glk:mylastduchess              My Last Duchess
glk:mythtale                   MythTale
glk:nameless                   Endless, Nameless
glk:nascarexperience           The Realistic Nascar eXperience
glk:nautilisia                 Nautilisia
glk:nemeanlion                 The Nemean Lion: another anonymous joke game
glk:neonnirvana                NEON NIRVANA
glk:neverplayed                So, You've Never Played a Text Adventure Before, Huh?
glk:newday                     A New Day
glk:nidus                      Nidus
glk:nightbunnies               The Night of the Vampire Bunnies
glk:nightchristmas             An Abbreviated Night Before Christmas
glk:nightcomputer              Night at the Computer Center
glk:nihilism                   The Abyss
glk:ninepoints                 Nine Points
glk:ninjasfate                 Ninja's Fate
glk:njag                       Not Just A Game
glk:njag2                      Not Just A Game 2
glk:noroom                     No Room
glk:northnorth                 The Northnorth Passage
glk:notinvenice                Not in Venice
glk:nudistsgonewild            Nudists Gone Wild
glk:oad                        Only After Dark
glk:oceantower                 Love, Hate and the Mysterious Ocean Tower
glk:odieus                     Odieus's Quest for the Magic Flingshot (Beta)
glk:ogisoas                    One Game in Search of a Story
glk:omniquest                  Omniquest
glk:onegirl                    One Girl
glk:onoptimism                 On Optimism
glk:onyourback                 On Your Back
glk:openingnight               Opening Night
glk:order00                    Order
glk:orevore                    Orevore Courier
glk:orion                      The Orion Agenda
glk:ottumwa                    PDFA Ottumwa
glk:outofthepit                Out of the Pit
glk:packrat                    Packrat
glk:paddlingmania              Total Paddling Mania
glk:paint                      Paint and Corners
glk:palebluelight              Pale Blue Light
glk:paperbagprincess           The Paper Bag Princess
glk:paperchase                 Paper Chase
glk:papermoon                  A Paper Moon
glk:parallel                   Parallel
glk:paranoia                   Paranoia
glk:parc                       Parc
glk:pasdedeux                  Pas De Deux
glk:pathfinder                 PATHFINDER
glk:pathway                    Pathway to Destruction
glk:peacock                    Not Made With Hands
glk:penandpaint                Pen and Paint
glk:pentari                    Pentari
glk:penury                     The Algophilists' Penury
glk:perilousmagic              Perilous Magic
glk:perrysworld                Perry's World
glk:pets                       Pets
glk:pfrank                     PROFESSOR FRANK
glk:phantomcaverns             Phantom: Caverns of the killer
glk:philosophersstone          The Quest for the Philosopher's Stone
glk:phlegm                     Phlegm
glk:photographportrait         Photograph, a Portrait of Reflection
glk:photograph                 PHOTOGRAPH
glk:photopia                   Photopia
glk:piece                      Piece of Mind
glk:pigpancake                 Pigpancake
glk:piracy2                    Piracy 2.0 - A Text Adventure in Space
glk:piraterailroad             Pirate Railroad
glk:playtorn                   Chronicle Play Torn
glk:polendina                  Polendina
glk:praser5                    Praser 5
glk:pressedon                  I pressed on, being chased by a stapler with my name on it
glk:priceoffreedom             The Price of Freedom
glk:primer                     Primer
glk:primrose                   The Primrose Path
glk:prize                      The Prize
glk:probing                    Offensive Probing
glk:promoted                   Promoted!
glk:psycheslament              Psyche's Lament
glk:puerto                     The board game Puerto Rico
glk:punkpoints                 Punk Points
glk:puppetman                  The Puppet-Man (Larsoft Adventure number 5)
glk:putpbaa                    Pick Up the Phone Booth and Aisle
glk:pytho                      Pytho's Mask
glk:quidditch1954              The Quidditch Final of 1954
glk:quietevening               A Quiet Evening at Home
glk:rachaelbadday              Rachel has a bad day
glk:ralph                      Ralph, An Interactive Sniffing
glk:rameses                    Rameses, a Tale of Heroes
glk:ramonandjonathan           Ramón and Jonathan
glk:rans                       RANS, an interworld progress
glk:ranshints                  RANS Hints
glk:readinginmay               A Reading in May
glk:reddex                     Reddex
glk:redmoonz                   Red Moon
glk:relief                     The Hunt For Relief
glk:rentaspy                   Rent-A-Spy
glk:reorsbushcave              Reor's Bush-Cave (The Sprout Pouch pt 4)
glk:reser                      Rock'Em Sock'Em Robots
glk:resident                   The Resident
glk:retrofatale                Retro Fatale
glk:revenger                   Revenger
glk:reverb                     Reverberations
glk:reverzi                    Reverzi
glk:ribbons                    Ribbons
glk:risenecropolis             Rise of the Necropolis
glk:risorg                     Risorgimento Represso
glk:riverside                  Riverside
glk:robotempire                Holy Robot Empire
glk:robots                     Robots - Another Abuse of the Z-Machine
glk:rogue                      zRogue
glk:roomserial                 Room Serial, an escape game
glk:rota                       The Reliques of Tolti-Aph
glk:rpn                        RPN
glk:rtdoom                     Return to Doom
glk:ruins                      Ruins
glk:samegame                   SameGame, another episode in the Z-Machine abuse saga
glk:samhain                    Samhain: Pick Up The Pumpkin and KILL
glk:samuelgregor               The Case of Samuel Gregor
glk:sanddancer                 Sand-dancer
glk:sangraal                   Sangraal
glk:santaland                  Escape from Santaland
glk:santassleighride           Santa's Sleigh Ride
glk:saveprinceton              Save Princeton
glk:savoirfaire                Savoir-Faire
glk:scald                      Scald
glk:schooldays                 Schooldays
glk:scopa                      Scopa, a graphical (Z-code V6) card game
glk:screen                     Screen
glk:seeksorrow                 Starry Seeksorrow
glk:sfiction                   Speculative Fiction: Beginner's Lessons
glk:shade                      Shade
glk:shadowgatez                Shadowgate
glk:shadowofmemories           Shadow of Memories
glk:shadowsoldiers             Shadow Soldiers
glk:shallow                    Shallow
glk:shamulet                   Scary House Amulet
glk:sheepcrossing              Sheep Crossing
glk:sherbet                    The Meteor, the Stone and a Long Glass of Sherbet
glk:sherlock1                  Sherlock gamebook #1: Murder at the Diogenes Club
glk:sherlock2                  Sherlock gamebook #2: The Black River Emerald
glk:sherlock3                  Sherlock gamebook #3: Death at Appledore Towers
glk:sherlock4                  Sherlock gamebook #4: The Crown vs Dr. Watson
glk:shipofwhimsy               Ship of Whimsy
glk:shrapnel                   Shrapnel
glk:siliconcastles             Silicon Castles
glk:simpletheft2               A Simple Theft 2: A Simple Theftier
glk:sisyphus                   Sisyphus
glk:sixgrayrats                Six Gray Rats Crawl Up The Pillow
glk:slackerx                   Slacker X
glk:sleepcycle                 Sleep Cycle
glk:slouchingbedlam            Slouching Towards Bedlam
glk:smallroom                  Trapped in a Small Room
glk:snacktime                  Snack Time!
glk:snafufun                   SNAFUFUN
glk:snowedin                   Snowed In
glk:snatches                   SNATCHES
glk:snowquest                  Snowquest
glk:soa                        Son of a...
glk:sofar                      So Far, An Interactive Catharsis
glk:softporn                   Softporn Adventure
glk:solitary                   Solitary
glk:somewhere                  Somewhere
glk:soreality                  So Reality
glk:spaceinvaderz              Space InvaderZ
glk:spacestation               Space Station: based on Planetfall example transcript
glk:spadventure                SpAdventure
glk:spelunkersquest            Spelunker's Quest
glk:spiderandweb               Spider And Web
glk:spiral                     Spiral
glk:spiritwrak                 SpiritWrak
glk:splashdown                 SPLASHDOWN
glk:sporkery1                  Sporkery 1: There Will Be Sporking
glk:spot                       The Spot
glk:spotlight                  The Spotlight
glk:spring                     She's Got a Thing For a Spring
glk:spring2020                 Spring 2020
glk:spycatcher                 Spycatcher
glk:stackoverflow              STACK OVERFLOW
glk:starborn                   Starborn
glk:starcity                   Star City
glk:stargods                   The Star Gods
glk:starhunter                 Star Hunter
glk:starlightz                 starlight
glk:stealingthestolen          Stealing the Stolen
glk:stewgoing                  You've Got A Stew Going!
glk:stiffmst                   Stiffy Makane: Mystery Science Theater 3000
glk:stiffy                     The Incredible Erotic Adventures of Stiffy Makane!
glk:stingwasp                  Sting of the Wasp
glk:stinkorswim                Stink or Swim
glk:stonecave                  The Stone Cave
glk:stormcellar                Storm Cellar
glk:strangegeometries          Strange Geometries
glk:strangeworld               Strange World
glk:suicide                    Suicide, a self-ordered death sentence
glk:summerland                 Escape from Summerland
glk:sunburn                    Sunburn
glk:sunburst                   Sunburst: A C64 science fiction adventure game
glk:sundayafternoon            Sunday Afternoon
glk:sushi                      A Day For Fresh Sushi
glk:sutwin                     The Space Under the Window
glk:suvehnux                   Suveh Nux
glk:swineback                  Swineback Ridge
glk:swordofmalice              THE SWORD OF MALICE
glk:sycamoratree               Sycamora Tree
glk:taipan                     Taipan!
glk:takethedogout              Take the Dog Out
glk:talemorning                The Mundane Tale of the Morning After
glk:tapestry                   Tapestry
glk:tatctae                    Time: All things come to an end
glk:tauntingdonut              Taunting Donut
glk:tblw                       The Blood lust Warrior
glk:tcomremake                 The Colour of Magic remake
glk:tcoty                      The Citizen of the Year
glk:teacherfeature             Teacher Feature
glk:telling                    Whom The Telling Changed
glk:temple                     The Temple
glk:tenthplague                Tenth Plague
glk:terribleoldmanse           The Terrible Old Manse: 8bit fun in 7bit ASCII
glk:terrortabby                Attack of the Terror Tabby!
glk:tesseract                  Beyond The Tesseract
glk:testisready                The Test is Now READY
glk:tgm                        The Great Machine - a fragment
glk:thatdamnelevator           That Damn Elevator
glk:thatdamnremote             thatdamnremote
glk:the5continent              The Fifth Continent
glk:theatre                    Theatre
glk:thecomputerlady            The Computer Lady
glk:theenchantedcastle         The Enchanted Castle
glk:thegrandquest              The Grand Quest
glk:thegrandtour               The Grand Tour
glk:thegreat                   The Great, A Voyage To The Inner Self
glk:theguardian                The Guardian
glk:theimmortal                The Immortal
glk:theimpossiblebottle        The Impossible Bottle
glk:theinvestment              The Investment
glk:thejob                     The Job
glk:thelighthouse              The Lighthouse
glk:thelucubrator              The Lucubrator
glk:themall                    The Mall
glk:thesproutpouch             Reor's Bush-Cave: The Sprout Pouch
glk:thetempest                 The Tempest
glk:thetemple                  The Temple
glk:thewedding                 The Wedding
glk:thorn                      The Thorn
glk:threecows                  Three Cows and Two Doors
glk:threediopolis              Threediopolis
glk:threemore                  Three More Visitors
glk:timefortea                 Time For Tea: A Game of Tea, Cakes, and Deadly Secrets
glk:tirehoax                   My Magic Tire Hoax
glk:tk1                        Time Killer #1: Claustrophobia
glk:tkatc                      The King and the Crown, Special Edition
glk:toask                      Treasures of a Slaver's Kingdom
glk:tok                        ToK
glk:tookiessong                TOOKiE'S SONG
glk:toughbeans                 Tough Beans
glk:tower                      Tower, a surreal trip
glk:towerofelephant            The Tower of the Elephant
glk:townmusicians              The Town Musicians
glk:toxinx                     Toxin X
glk:trapped                    Trapped
glk:trein                      Trein
glk:tristamisland              Tristam Island (Demo)
glk:troll                      Zork: A Troll's Eye View
glk:trw                        Tull Road Warrior
glk:trystoffate                Tryst of Fate
glk:tubetrouble                Tube Trouble
glk:tundra                     Tundra
glk:tutorial                   Tutorial
glk:tutorialhotel              Hotel Tutorial
glk:tuuli                      Tuuli
glk:typo                       Typo!
glk:uhohdemo                   Uh-oh! (demo version)
glk:umw                        UMW
glk:underdoos                  The Underoos that ate New York!
glk:undergroundz               Underground
glk:underthebed                Under the Bed
glk:unforgotten                Unforgotten
glk:ungodlyhour                Ungodly hour
glk:unicornpool                The Unicorn Pool
glk:uninvited                  UNINVITED
glk:vacation                   Vacation Gone Awry
glk:vagueness                  What Happens In Vagueness
glk:vampiresun                 House of the Midnight Sun - A Vampire's Tale
glk:varicella                  Varicella
glk:vergingpaths               The Garden of Verging Paths
glk:vespers                    Vespers
glk:vestiges                   Vestiges
glk:vigilance                  Internal Vigilance
glk:vindaloo                   Vindaloo
glk:violet                     Violet
glk:virtuality                 Virtuality
glk:visitor                    The Visitor
glk:vosr                       Voices of Spoon River
glk:wadewar3                   The WadeWars Book III
glk:walkamongus                Walk Among Us
glk:walkinthepark              A Walk in the Park
glk:wallpaper                  Delightful Wallpaper
glk:warblersnest               The Warbler's Nest
glk:warp                       Warp!
glk:weapon                     The Weapon
glk:weareunfinished            We Are Unfinished
glk:weather                    A Change in the Weather
glk:weding                     Wedding
glk:weirdcity                  Weird City Interloper
glk:weirdness                  Weirdness: Strange, Different, and Altogether Weird
glk:welcometohell              Welcome to Hell
glk:welcometopuerto            Welcome to Puerto Rico
glk:wernersquest1              Werner's Quest Parts 1
glk:wernersquest2              Werner's Quest Parts 2
glk:wernersquest3              Werner's Quest Parts 3
glk:wernersquest4              Werner's Quest Parts 4
glk:whenhelpcollides           When Help Collides
glk:whenmachinesattack         wHen mAchines aTtack
glk:whispers                   The Corn Identity, an "IF Whispers" collaborative project
glk:whitehouses                White Houses
glk:wildflowers                Wildflowers
glk:williamtell                William Tell
glk:winchester                 Winchester's Nightmare
glk:windhall                   The Windhall Chronicles, Volume One
glk:winterwonderland           Winter Wonderland
glk:wir1                       When in Rome 1: Accounting for Taste
glk:wir2                       When in Rome 2: Far from Home
glk:wireless                   Get Magazine. Open Magazine. Read Article
glk:wish                       Wish
glk:wizardscastle              Wizard's Castle
glk:worldupsidedown            The World Turned Upside Down
glk:wossname                   Spodgeville Murphy and The Jewelled Eye of Wossname
glk:wrenlaw                    Wrenlaw
glk:wscholars                  Weishaupt Scholars
glk:wump2ka                    Wumpus 2000, The Virulent Labyrinth Of Yob-Shuggoth
glk:wumpus                     Hunt the Wumpus
glk:wurm                       Wurm
glk:wwwanderer                 Werewolves and Wanderer
glk:xenophobia                 Xenophobia
glk:yagwad                     YAGWAD: Yes, Another Game With A Dragon!
glk:yakshaving                 Yak Shaving for Kicks and Giggles!
glk:yomomma                    Raising the Flag on Mount Yo Momma
glk:zassball                   ZassBall, Another Abuse of the Z-Machine
glk:zbefunge                   ZBefunge 0.7 beta
glk:zcamel                     Camel
glk:zcatalog                   The Z-Files, a Z-Code Catalog
glk:zchess                     Z-Chess
glk:zdungeon                   ZDungeon
glk:zedfunge                   ZedFunge 0.7.3 beta
glk:zedit                      ZEdit, The World's Most Portable Text Editor
glk:zegro                      Zegrothenus
glk:zenon                      Escape from the Starship Zenon
glk:zenspeak                   Zen Speaks!
glk:zlife                      Z-Life
glk:zokoban                    Z-Machine Sokoban
glk:zombies                    Zombies, yet another abuse of the Z-Machine
glk:zork285                    Zork 285 Points Replica
glk:zorkburiedchaos            Welcome to zork, buried chaos
glk:zorkianstories1            Zorkian Stories 1: G.U.E
glk:zorklxix                   Zork LXIX: The Great Underground Hot Dog
glk:zorknplus9                 Zork N plus 9
glk:zpegasus                   Pegasus
glk:zracer                     ZRacer
glk:zsnake                     Z-Snake
glk:ztornado                   Z-Tornado
glk:ztrek                      Super Z Trek
glk:zugzwang                   Zugzwang: The Interactive Life of a Chess Piece
glk:zunidoll                   The Zuni Doll
glk:plsg1                      Dinnertime: Painless Little Stupid Games #1
glk:plsg2                      To Get To The Other Side: Painless Little Stupid Games #2
glk:plsg3                      They're After You!: Painless Little Stupid Games #3
glk:plsg4                      Mazemapper: Painless Little Stupid Games #4
glk:plsg5                      The Mean Story: Painless Little Stupid Games #5
glk:plsg6                      Mahadev: Painless Little Stupid Games #6
glk:plsg7                      Sturdlint: Painless Little Stupid Games #7
glk:plsg8                      The Last Dark Day: Painless Little Stupid Games #8
glk:plsg9                      Zork LXIX: Painless Little Stupid Games #9
glk:plsg10                     The Valley House: Painless Little Stupid Games #10
glk:adventurelandi5            Adventureland
glk:pirateadventurei5          Pirate Adventure
glk:missionimpossiblei5        Mission Impossible
glk:voodoocastlei5             Voodoo Castle
glk:thecounti5                 The Count
glk:strangeodysseyi5           Strange Odyssey
glk:mysteryfunhousei5          Mystery Fun House
glk:pyramidofdoomi5            Pyramid Of Doom
glk:ghosttowni5                Ghost Town
glk:savageisland1i5            Savage Island, Part 1
glk:savageisland2i5            Savage Island, Part 2
glk:goldenvoyagei5             The Golden Voyage
glk:adventure13i5              Adventure 13
glk:adventure14i5              Adventure 14
glk:buckaroobanzaii5           Buckaroo Banzai
glk:marveladventurei5          Marvel Adventure #1
glk:questprobe2i5              Questprobe 2: Spiderman
glk:scottsampleri5             Adventure International's Mini-Adventure Sampler
glk:goldenbatoni5              Mysterious Adventures 1: The Golden Baton
glk:timemachinei5              Mysterious Adventures 2: The Time Machine
glk:arrowofdeath1i5            Mysterious Adventures 3: Arrow of Death Part 1
glk:arrowofdeath2i5            Mysterious Adventures 4: Arrow of Death Part 2
glk:pulsar7i5                  Mysterious Adventures 5: Escape from Pulsar 7
glk:circusi5                   Mysterious Adventures 6: Circus
glk:feasibilityi5              Mysterious Adventures 7: Feasibility Experiment
glk:akyrzi5                    Mysterious Adventures 8: The Wizard of Akyrz
glk:perseusi5                  Mysterious Adventures 9: Perseus and Andromeda
glk:10indiansi5                Mysterious Adventures 10: Ten Little Indians
glk:waxworksi5                 Mysterious Adventures 11: Waxworks
glk:apollo1                    Apollo 18 01: Dig My Grave
glk:apollo2                    Apollo 18 02: I Palindrome I
glk:apollo3                    Apollo 18 03: She's Actual Size
glk:apollo4                    Apollo 18 04: My Evil Twin
glk:apollo5                    Apollo 18 05: Mammal
glk:apollo6                    Apollo 18 06: The Statue Got Me High
glk:apollo7                    Apollo 18 07: Spider
glk:apollo8                    Apollo 18 08: The Guitar(The Lion Sleeps Tonight)
glk:apollo9                    Apollo 18 09: Dinner Bell
glk:apollo10                   Apollo 18 10: Narrow Your Eyes
glk:apollo11                   Apollo 18 11: Hall of Heads
glk:apollo12                   Apollo 18 12: Which Describes How You're Feeling
glk:apollo13                   Apollo 18 13: See the Constellation
glk:apollo14                   Apollo 18 14: If I Wasn't Shy
glk:apollo15                   Apollo 18 15: Turn Around
glk:apollo16                   Apollo 18 16: Hypnotist of Ladies
glk:apollo17                   Apollo 18 17: Fingertips - Everything Is Catching on Fire
glk:apollo18                   Apollo 18 18: Fingertips - Fingertips
glk:apollo19                   Apollo 18 19: Fingertips - I Hear the Wind Blow
glk:apollo20                   Apollo 18 20: Fingertips - Hey Now, Everybody
glk:apollo21                   Apollo 18 21: Fingertips - Who's That Standing Out the Window
glk:apollo22                   Apollo 18 22: Fingertips - I Found a New Friend
glk:apollo23                   Apollo 18 23: Fingertips - Come On and Wreck My Car
glk:apollo24                   Apollo 18 24: Fingertips - Aren't You the Guy Who Hit Me in the Eye
glk:apollo25                   Apollo 18 25: Fingertips - Please Pass the Milk Please
glk:apollo26                   Apollo 18 26: Fingertips - Leave Me Alone
glk:apollo27                   Apollo 18 27: Fingertips - Who's Knockin' on the Wall
glk:apollo28                   Apollo 18 28: Fingertips - All Alone
glk:apollo29                   Apollo 18 29: Fingertips - What's That Blue Thing Doing Here
glk:apollo30                   Apollo 18 30: Fingertips - Something Grabbed Ahold of My Hand
glk:apollo31                   Apollo 18 31: Fingertips - I Don't Understand You
glk:apollo32                   Apollo 18 32: Fingertips - I Heard a Sound
glk:apollo33                   Apollo 18 33: Fingertips - Mysterious Whisper
glk:apollo34                   Apollo 18 34: Fingertips - The Day That Love Came to Play
glk:apollo35                   Apollo 18 35: Fingertips - I'm Having a Heart Attack
glk:apollo36                   Apollo 18 36: Fingertips - Fingertips(Reprise)
glk:apollo37                   Apollo 18 37: Fingertips - I Walk Along Darkened Corridors
glk:apollo38                   Apollo 18 38: Space Suit
glk:nissen                     Pa loftet sidder nissen
glk:championdebasketball       Champion de basket-ball
glk:dreamlands                 Echappee Belle Dans Les Contrees du Reve
glk:espions                    Les espions ne meurent jamais
glk:filaments                  Filaments
glk:initiation                 Initiation
glk:interra                    INTERRA - L'autre monde
glk:kheper                     Kheper
glk:verdeterre                 Le butin du Capitaine Verdeterre
glk:lecercledesgros            Le Cercle des Gros Geeks disparus
glk:lieuxcommuns               Lieux communs
glk:lmpsd                      La Mort Pour Seul Destin
glk:ombre                      Ombre
glk:princesse                  Ma princesse adoree
glk:sarvegne                   Sarvegne
glk:katana                     Le Scarabee et le Katana
glk:sdlc                       Sortir de la chambre
glk:balcon                     Sorciere au balcon
glk:templedefeu                Le Temple de Feu
glk:bearg                      Ein Bar Geht Aus
glk:bewerbung                  Die Bewerbung
glk:deklinator                 Object declination tool
glk:edendemo                   Der Abentheurliche Informissimus Teutsch demo
glk:halb2                      Halb Zwei
glk:herr                       Die Geschichte des Herrn P. von Hannes Schuller
glk:jazteg                     Jazz auf Tegemis
glk:karisma                    Klub Karisma
glk:knack                      Knack!
glk:o                          O
glk:starrider                  Star Rider
glk:mchatton                   Tutorial Eine Einfuhrung in Textadventures von Cooper McHatton
glk:wasserhasser               Wasser-Hasser
glk:wichtel                    Wichtel
glk:aldila                     Beyond
glk:armando                    L'Armando
glk:ayon                       Nel Mondo di Ayon
glk:darkiss                    Darkiss! Il bacio del vampiro
glk:darkiss2                   Darkiss! Il bacio del vampiro. Capitolo 2
glk:filamit                    Filaments
glk:flamel                     Flamel
glk:giardino                   Il giardino incantato
glk:kangourou                  Kangourou dell'informatica 2013
glk:koohinoor                  Kooh-I-Noor
glk:luna                       La Pietra della Luna
glk:poesia                     Manca solo un verso a quella poesia
glk:oldwest1                   Pecos Town, Old West Episode I
glk:rovo                       Il rovo
glk:scarafaggio                Lo Scarafaggio
glk:sognodisangue              Sogno di Sangue
glk:strega                     La strega di Maughn
glk:tesla                      In Cerca Di Tesla
glk:villamorgana               Villa Morgana
glk:zazie                      Zazie, una lettura interattiva
glk:zenfactorspa               ZenFactor Spa
glk:zombie                     Uno Zombie a Deadville
glk:zorkita                    Zork I: Il Grande Impero Sotterraneo
glk:zenin                      Zenin na begu
glk:abalanzate                 Abalanzate
glk:absolutos                  Los sonidos absolutos
glk:afuera                     Afuera
glk:amanda                     Amanda
glk:aque1                      Aquelarre
glk:casi                       Casi Muerto
glk:celos                      Un Asunto de Celos
glk:cerillera                  La Pequena Cerillera
glk:churro                     Churro patatero
glk:csa                        Cacahuetes
glk:cueva                      La Oscura Cueva
glk:ddddddcrj                  Cirith Ungol
glk:despert                    El Despertar
glk:draculasp2                 Dracula: Episodio 2, La Llegada
glk:draculasp                  Dracula: Episodio 1, La Primera Noche
glk:ascenso                    El ascenso de Kunelar
glk:regalo                     El regalo de Gorbag
glk:encierro                   Encierro
glk:elultimohogar              Misterio en el Ultimo Hogar
glk:ergotdelima                Lime Ergot
glk:forrajeo                   Forrajeo
glk:fotopia                    Fotopia
glk:gorbag                     El regalo de Gorbag
glk:gorron                     El gorron del tren
glk:goteras                    Goteras
glk:hhorcus                    Homo Homini Orcus
glk:islas                      El archipielago
glk:kerulen                    Ke rulen los petas, por Grendelkhan
glk:konix                      Konix
glk:kunelar                    El ascenso de Kunelar
glk:lamansion                  La Mansion
glk:libroaburria               El libro que se aburría
glk:lldc                       La Llamada de Cthulhu
glk:macetas                    Macetas
glk:meeva                      La mediana evasion
glk:megara                     Los placeres de Megara
glk:modusvivendi               An ancient Roman tale
glk:mpdroidone                 Operacion MPDroid1
glk:navidad                    Una pequena historia de Navidad
glk:necedad                    Por la Necedad Humana
glk:culpatuya                  No es culpa tuya Maria
glk:ocaso                      Ocaso Mortal I: The Bug
glk:oculta                     La cara oculta de la luna
glk:olvido                     Olvido Mortal
glk:osito                      La Intrepida Noche del Osito
glk:panajo                     Pan de Ajo, by Incanus
glk:pesadillavoraz             Pesadilla voraz
glk:pincoya                    Ofrenda a La Pincoya
glk:playera                    En la playa
glk:protector                  El Protector
glk:reflejos                   Reflejos blancos
glk:senten                     La Sentencia
glk:sombras                    Sombras de Moria
glk:tokland                    La isla de Tokland
glk:torre                      Misterio en la torre
glk:aventyr                    Aventyr
glk:drakmagi                   Drakmagi
glk:hotellet                   Hotel Noir
glk:pangnyheten                Pangnyheten
glk:storforsen                 Storforsen
glk:stuga                      Stuga
glk:vanyar                     Vanyar
gnap:gnap                      Gnap
gob:gob1                       Gobliiins
gob:gob1cd                     Gobliiins CD
gob:gob2                       Gobliins 2
gob:gob2cd                     Gobliins 2 CD
gob:ween                       Ween: The Prophecy
gob:bargon                     Bargon Attack
gob:babayaga                   Once Upon A Time: Baba Yaga
gob:abracadabra                Once Upon A Time: Abracadabra
gob:littlered                  Once Upon A Time: Little Red Riding Hood
gob:onceupon                   Once Upon A Time
gob:ajworld                    A.J.'s World of Discovery
gob:gob3                       Goblins Quest 3
gob:gob3cd                     Goblins Quest 3 CD
gob:crousti                    Croustibat
gob:lit1                       Lost in Time Part 1
gob:lit2                       Lost in Time Part 2
gob:lit                        Lost in Time
gob:inca2                      Inca II: Wiracocha
gob:woodruff                   The Bizarre Adventures of Woodruff and the Schnibble
gob:dynasty                    The Last Dynasty
gob:dynastywood                Woodruff and The Last Dynasty
gob:urban                      Urban Runner
gob:playtoons1                 Playtoons 1 - Uncle Archibald
gob:playtoons2                 Playtoons 2 - The Case of the Counterfeit Collaborator
gob:playtoons3                 Playtoons 3 - The Secret of the Castle
gob:playtoons4                 Playtoons 4 - The Mandarine Prince
gob:playtoons5                 Playtoons 5 - The Stone of Wakan
gob:playtnck1                  Playtoons Construction Kit 1 - Monsters
gob:playtnck2                  Playtoons Construction Kit 2 - Knights
gob:playtnck3                  Playtoons Construction Kit 3 - Far West
gob:bambou                     Playtoons Limited Edition - Bambou le sauveur de la jungle
gob:fascination                Fascination
gob:geisha                     Geisha
gob:adi2                       ADI 2
gob:adi4                       ADI 4
gob:adibou2                    Adibou 2
gob:adibou1                    Adibou 1
griffon:griffon                The Griffon Legend
grim:grim                      Grim Fandango
grim:monkey4                   Escape From Monkey Island
groovie:t7g                    The 7th Guest
groovie:11h                    The 11th Hour: The Sequel to The 7th Guest
groovie:making11h              The Making of The 11th Hour
groovie:clandestiny            Clandestiny
groovie:unclehenry             Uncle Henry's Playhouse
groovie:tlc                    Tender Loving Care
hadesch:hadesch                Hades Challenge
hdb:hdb                        Hyperspace Delivery Boy!
hopkins:hopkins                Hopkins FBI
hugo:hugo1                     Hugo 1: Hugo's House of Horrors
hugo:hugo2                     Hugo 2: Whodunit?
hugo:hugo3                     Hugo 3: Jungle of Doom
hypno:sinistersix              Marvel Comics Spider-Man: The Sinister Six
hypno:wetlands                 Wetlands
hypno:soldierboyz              Soldier Boyz
hypno:teacher                  Bruce Coville's My Teacher Is an Alien
icb:icb                        In Cold Blood
icb:eldorado                   The Road to El Dorado
illusions:bbdou                Beavis and Butt-head Do U
illusions:duckman              Duckman
kingdom:kingdom                Kingdom: The Far Reaches
kyra:kyra1                     The Legend of Kyrandia
kyra:kyra2                     The Legend of Kyrandia: The Hand of Fate
kyra:kyra3                     The Legend of Kyrandia: Malcolm's Revenge
kyra:lol                       Lands of Lore: The Throne of Chaos
kyra:eob                       Eye of the Beholder
kyra:eob2                      Eye of the Beholder II: The Legend of Darkmoon
lab:lab                        Labyrinth of Time
lastexpress:lastexpress        The Last Express
lilliput:robin                 Adventures of Robin Hood
lilliput:rome                  Rome: Pathway to Power
lure:lure                      Lure of the Temptress
macventure:shadowgate          Shadowgate
macventure:deja_vu             Deja Vu
macventure:deja_vu2            Deja Vu II
macventure:uninvited           Uninvited.
made:manhole                   The Manhole
made:rtz                       Return to Zork
made:lgop2                     Leather Goddesses of Phobos 2
made:rodney                    Rodney's Funscreen
mads:dragonsphere              Dragonsphere
mads:nebular                   Rex Nebular and the Cosmic Gender Bender
mads:phantom                   Return of the Phantom
mohawk:myst                    Myst
mohawk:makingofmyst            The Making of Myst
mohawk:riven                   Riven: The Sequel to Myst
mohawk:cstime                  Where in Time is Carmen Sandiego?
mohawk:carmentq                Carmen Sandiego's ThinkQuick Challenge
mohawk:carmentqc               Carmen Sandiego's ThinkQuick Challenge Custom Question Creator
mohawk:maggiesfa               Maggie's Farmyard Adventure
mohawk:greeneggs               Green Eggs and Ham
mohawk:seussabc                Dr Seuss's ABC
mohawk:seussps                 Dr Seuss's Preschool
mohawk:tortoise                Aesop's Fables: The Tortoise and the Hare
mohawk:arthur                  Arthur's Teacher Trouble
mohawk:grandma                 Just Grandma and Me
mohawk:ruff                    Ruff's Bone
mohawk:newkid                  The New Kid on the Block
mohawk:arthurrace              Arthur's Reading Race
mohawk:arthurbday              Arthur's Birthday
mohawk:lilmonster              Little Monster at School
mohawk:catinthehat             The Cat in the Hat
mohawk:rugrats                 Rugrats Adventure Game
mohawk:lbsampler               Living Books Sampler
mohawk:bearfight               The Berenstain Bears Get in a Fight
mohawk:beardark                The Berenstain Bears In The Dark
mohawk:arthurcomp              Arthur's Computer Adventure
mohawk:create                  The Story of Creation
mohawk:daniel                  Daniel in the Lions' Den
mohawk:harryhh                 Harry and the Haunted House
mohawk:stellaluna              Stellaluna
mohawk:sheila                  Sheila Rae, the Brave
mohawk:rugratsps               Rugrats Print Shop
mohawk:wsg                     Williams-Sonoma Guide to Good Cooking
mortevielle:mortevielle        Mortville Manor
mtropolis:obsidian             Obsidian
mtropolis:mti                  Muppet Treasure Island
mutationofjb:mutationofjb      Mutation of J.B.
myst3:myst3                    Myst III Exile
nancy:vampirediaries           The Vampire Diaries
nancy:nancy1                   Nancy Drew: Secrets Can Kill
nancy:nancy2                   Nancy Drew: Stay Tuned for Danger
nancy:nancy3                   Nancy Drew: Message in a Haunted Mansion
nancy:nancy4                   Nancy Drew: Treasure in the Royal Tower
nancy:nancy5                   Nancy Drew: The Final Scene
nancy:nancy6                   Nancy Drew: Secret of the Scarlet Hand
neverhood:neverhood            The Neverhood Chronicles
ngi:ngi                        Nikita Game Interface game
ngi:fullpipe                   Full Pipe
ngi:mdream                     Magic Dream
parallaction:nippon            Nippon Safes Inc.
parallaction:bra               The Big Red Adventure
pegasus:pegasus                The Journeyman Project: Pegasus Prime
petka:petka_demo               Red Comrades Demo
petka:petka1                   Red Comrades 1: Save the Galaxy
petka:petka2                   Red Comrades 2: For the Great Justice
pink:peril                     The Pink Panther: Passport to Peril
pink:pokus                     The Pink Panther: Hokus Pokus Pink
playground3d:playground3d      Playground 3d: the testing and playground environment for 3d renderers
plumbers:plumbers              Plumbers Don't Wear Ties!
prince:prince                  The Prince and the Coward
private:private-eye            Private Eye
queen:queen                    Flight of the Amazon Queen
saga:ite                       Inherit the Earth: Quest for the Orb
saga:ihnm                      I Have No Mouth and I Must Scream
saga2:dino                     Dinotopia
saga2:fta2                     Faery Tale Adventure II: Halls of the Dead
sci:sci                        Sierra SCI Game
sci:sci-fanmade                Fanmade SCI Game
sci:astrochicken               Astro Chicken
sci:christmas1988              Christmas Card 1988
sci:iceman                     Codename: Iceman
sci:camelot                    Conquests of Camelot: King Arthur, Quest for the Grail
sci:funseeker                  Fun Seeker's Guide
sci:hoyle1                     Hoyle Official Book of Games: Volume 1
sci:hoyle2                     Hoyle Official Book of Games: Volume 2
sci:kq4sci                     King's Quest IV: The Perils of Rosella
sci:laurabow                   Laura Bow: The Colonel's Bequest
sci:lsl2                       Leisure Suit Larry 2: Goes Looking for Love (in Several Wrong Places)
sci:lsl3                       Leisure Suit Larry 3: Passionate Patti in Pursuit of the Pulsating Pectorals
sci:mothergoose                Mixed-Up Mother Goose
sci:pq2                        Police Quest II: The Vengeance
sci:qfg1                       Quest for Glory I: So You Want to Be a Hero
sci:sq3                        Space Quest III: The Pirates of Pestulon
sci:qfg2                       Quest for Glory II: Trial by Fire
sci:kq1sci                     King's Quest I: Quest for the Crown
sci:castlebrain                Castle of Dr. Brain
sci:christmas1990              Christmas Card 1990: The Seasoned Professional
sci:cnick-lsl                  Crazy Nick's Software Picks: Leisure Suit Larry's Casino
sci:cnick-kq                   Crazy Nick's Software Picks: King Graham's Board Game Challenge
sci:cnick-laurabow             Crazy Nick's Software Picks: Parlor Games with Laura Bow
sci:cnick-longbow              Crazy Nick's Software Picks: Robin Hood's Game of Skill and Chance
sci:cnick-sq                   Crazy Nick's Software Picks: Roger Wilco's Spaced Out Game Pack
sci:ecoquest                   EcoQuest: The Search for Cetus
sci:fairytales                 Mixed-up Fairy Tales
sci:hoyle3                     Hoyle Official Book of Games: Volume 3
sci:jones                      Jones in the Fast Lane
sci:kq5                        King's Quest V: Absence Makes the Heart Go Yonder
sci:longbow                    Conquests of the Longbow: The Adventures of Robin Hood
sci:lsl1sci                    Leisure Suit Larry in the Land of the Lounge Lizards
sci:lsl5                       Leisure Suit Larry 5: Passionate Patti Does a Little Undercover Work
sci:mothergoose256             Mixed-Up Mother Goose
sci:msastrochicken             Ms. Astro Chicken
sci:pq1sci                     Police Quest: In Pursuit of the Death Angel
sci:pq3                        Police Quest III: The Kindred
sci:sq1sci                     Space Quest I: The Sarien Encounter
sci:sq4                        Space Quest IV: Roger Wilco and the Time Rippers
sci:christmas1992              Christmas Card 1992
sci:ecoquest2                  EcoQuest II: Lost Secret of the Rainforest
sci:freddypharkas              Freddy Pharkas: Frontier Pharmacist
sci:hoyle4                     Hoyle Classic Card Games
sci:inndemo                    ImagiNation Network (INN) Demo
sci:kq6                        King's Quest VI: Heir Today, Gone Tomorrow
sci:laurabow2                  Laura Bow 2: The Dagger of Amon Ra
sci:qfg1vga                    Quest for Glory I: So You Want to Be a Hero
sci:qfg3                       Quest for Glory III: Wages of War
sci:sq5                        Space Quest V: The Next Mutation
sci:islandbrain                The Island of Dr. Brain
sci:lsl6                       Leisure Suit Larry 6: Shape Up or Slip Out!
sci:pepper                     Pepper's Adventures in Time
sci:slater                     Slater & Charlie Go Camping
sci:gk1demo                    Gabriel Knight: Sins of the Fathers
sci:qfg4demo                   Quest for Glory IV: Shadows of Darkness
sci:pq4demo                    Police Quest IV: Open Season
sci:gk1                        Gabriel Knight: Sins of the Fathers
sci:pq4                        Police Quest IV: Open Season
sci:qfg4                       Quest for Glory IV: Shadows of Darkness
sci:hoyle5                     Hoyle Classic Games
sci:hoyle5bridge               Hoyle Bridge
sci:hoyle5children             Hoyle Children's Collection
sci:hoyle5solitaire            Hoyle Solitaire
sci:chest                      Inside the Chest
sci:gk2                        The Beast Within: A Gabriel Knight Mystery
sci:kq7                        King's Quest VII: The Princeless Bride
sci:kquestions                 King's Questions
sci:lsl6hires                  Leisure Suit Larry 6: Shape Up or Slip Out!
sci:mothergoosehires           Mixed-Up Mother Goose Deluxe
sci:phantasmagoria             Phantasmagoria
sci:pqswat                     Police Quest: SWAT
sci:realm                      The Realm
sci:shivers                    Shivers
sci:sq6                        Space Quest 6: The Spinal Frontier
sci:torin                      Torin's Passage
sci:lsl7                       Leisure Suit Larry 7: Love for Sail!
sci:lighthouse                 Lighthouse: The Dark Being
sci:phantasmagoria2            Phantasmagoria 2: A Puzzle of Flesh
sci:rama                       RAMA
sherlock:scalpel               The Case of the Serrated Scalpel
sherlock:rosetattoo            The Case of the Rose Tattoo
sky:sky                        Beneath a Steel Sky
sludge:sludge                  Sludge Game
sludge:welcome                 Welcome Example
sludge:verbcoin                Verb Coin
sludge:robinsrescue            Robin's Rescue
sludge:outoforder              Out Of Order
sludge:frasse                  Frasse and the Peas of Kejick
sludge:interview               The Interview
sludge:life                    Life Flashes By
sludge:tgttpoacs               The Game That Takes Place on a Cruise Ship
sludge:mandy                   Mandy Christmas Adventure
sludge:cubert                  Cubert Badbone, P.I.
sludge:gjgagsas                The Game Jam Game About Games, Secrets and Stuff
sludge:tsotc                   The Secret of Tremendous Corporation
sludge:nsc                     Nathan's Second Chance
sludge:atw                     Above The Waves
sludge:leptonsquest            Lepton's Quest
stark:tlj                      The Longest Journey
startrek:st25                  Star Trek: 25th Anniversary
startrek:stjr                  Star Trek: Judgment Rites
supernova:msn1                 Mission Supernova 1
supernova:msn2                 Mission Supernova 2
sword1:sword1                  Broken Sword: The Shadow of the Templars
sword1:sword1demo              Broken Sword: The Shadow of the Templars (Demo)
sword1:sword1mac               Broken Sword: The Shadow of the Templars (Mac)
sword1:sword1macdemo           Broken Sword: The Shadow of the Templars (Mac demo)
sword1:sword1psx               Broken Sword: The Shadow of the Templars (PlayStation)
sword1:sword1psxdemo           Broken Sword: The Shadow of the Templars (PlayStation demo)
sword2:sword2                  Broken Sword II: The Smoking Mirror
sword2:sword2alt               Broken Sword II: The Smoking Mirror (alt)
sword2:sword2psx               Broken Sword II: The Smoking Mirror (PlayStation)
sword2:sword2psxdemo           Broken Sword II: The Smoking Mirror (PlayStation/Demo)
sword2:sword2demo              Broken Sword II: The Smoking Mirror (Demo)
sword2:sword2demo-es           Broken Sword II: The Smoking Mirror (Spanish/Demo)
sword25:sword25                Broken Sword 2.5
teenagent:teenagent            Teen Agent
testbed:testbed                Testbed: The Backend Testing Framework
tinsel:dw                      Discworld
tinsel:dw2                     Discworld 2: Missing Presumed ...!?
tinsel:noir                    Discworld Noir
titanic:titanic                Starship Titanic
toltecs:toltecs                3 Skulls of the Toltecs
tony:tony                      Tony Tough and the Night of Roasted Moths
toon:toon                      Toonstruck
touche:touche                  Touche: The Adventures of the Fifth Musketeer
trecision:aot                  Ark of Time
trecision:nl                   Nightlong: Union City Conspiracy
tsage:ringworld                Ringworld: Revenge of the Patriarch
tsage:blueforce                Blue Force
tsage:ringworld2               Return to Ringworld
tsage:sherlock-logo            The Lost Files of Sherlock Holmes (Logo)
tucker:tucker                  Bud Tucker in Double Trouble
twine:lba                      Little Big Adventure
twine:lbashow                  Little Big Adventure Freeware Slide Show
twine:lba2                     Little Big Adventure 2
ultima:ultima4                 Ultima IV - Quest of the Avatar
ultima:ultima4_enh             Ultima IV - Quest of the Avatar - Enhanced
ultima:ultima6                 Ultima VI - The False Prophet
ultima:ultima6_enh             Ultima VI - The False Prophet - Enhanced
ultima:ultima8                 Ultima VIII - Pagan
ultima:remorse                 Crusader: No Remorse
ultima:regret                  Crusader: No Regret
ultima:martiandreams           Worlds of Ultima: Martian Dreams
ultima:martiandreams_enh       Worlds of Ultima: Martian Dreams - Enhanced
ultima:thesavageempire         Worlds of Ultima: The Savage Empire
ultima:thesavageempire_enh     Worlds of Ultima: The Savage Empire - Enhanced
voyeur:voyeur                  Voyeur
wage:afm                       Another Fine Mess
wage:amot                      A Mess O' Trouble
wage:cantitoe                  Camp Cantitoe
wage:drakmythcastle            Drakmyth Castle
wage:grailquest                GrailQuest: Adventure in the Age of King Arthur
wage:raysmaze                  Ray's Maze
wage:scepters                  Enchanted Scepters
wage:twisted                   Twisted!
wage:wage                      WAGE
wintermute:5ld                 Five Lethal Demons
wintermute:5ma                 Five Magical Amulets
wintermute:8squares            Eight Squares in The Garden
wintermute:actualdest          Actual Destination
wintermute:agustin             Boredom of Agustin Cordes
wintermute:alavi               Alavi Detective - Murder of Miss Rojan
wintermute:alimardan1          Alimardan's Mischief
wintermute:alimardan2          Alimardan Meets Merlin
wintermute:alone               Alone, Under Strange Night
wintermute:alphapolaris        Alpha Polaris
wintermute:apeiron             Apeiron
wintermute:artofmurder1        Art of Murder 1: FBI Confidential
wintermute:awakening           Awakening: Burning Ashes
wintermute:barbapoca1          El Engaño de Barbapoca Chapter 1: Esta Pizza Esta de Muerte
wintermute:barbapoca2          El Engaño de Barbapoca Chapter 2: Competencia Fantasmal
wintermute:barrowhilldp        Barrow Hill - The Dark Path
wintermute:basisoctavus        Basis Octavus
wintermute:bickadoodle         Bickadoodle
wintermute:bookmania           BookMania
wintermute:bookofgron          Book of Gron Part One
wintermute:bthreshold          Beyond the Threshold
wintermute:carolreed4          Carol Reed 4 - East Side Story
wintermute:carolreed5          Carol Reed 5 - The Colour of Murder
wintermute:carolreed6          Carol Reed 6 - Black Circle
wintermute:carolreed7          Carol Reed 7 - Blue Madonna
wintermute:carolreed8          Carol Reed 8 - Amber's Blood
wintermute:carolreed9          Carol Reed 9 - Cold Case Summer
wintermute:carolreed10         Carol Reed 10 - Bosch's Damnation
wintermute:carolreed11         Carol Reed 11 - Shades Of Black
wintermute:carolreed12         Carol Reed 12 - Profound Red
wintermute:carolreed13         Carol Reed 13 - The Birdwatcher
wintermute:carolreed14         Carol Reed 14 - The Fall Of April
wintermute:carolreed15         Carol Reed 15 - Geospots
wintermute:carolreed16         Carol Reed 16 - Quarantine Diary
wintermute:chaos               Chaos
wintermute:chivalry            Chivalry is Not Dead
wintermute:colapso1            Colapso: Episode 1
wintermute:colorsoncanvas      Colors on Canvas
wintermute:conspiracao         Conspiracao Dumont
wintermute:corrosion           Corrosion: Cold Winter Waiting
wintermute:darkfallls          Dark Fall: Lost Souls
wintermute:darksummer          Twilight: Dark Summer
wintermute:deadcity            Dead City
wintermute:devilincapital      Devil In The Capital
wintermute:dfafadventure       DFAF Adventure
wintermute:dirtysplit          Dirty Split
wintermute:drbohus             Dr. Bohus
wintermute:drdoylemotch        Dr. Doyle - Mystery Of The Cloche Hat
wintermute:dreamcat            Dreamcat
wintermute:dreaming            Des Reves Elastiques Avec Mille Insectes Nommes Georges
wintermute:dreams              Dreams
wintermute:dreamscape          Dreamscape
wintermute:driller             The Driller Incident
wintermute:erinmyers           The Death of Erin Myers
wintermute:escapemansion       Escape from the Mansion
wintermute:everydaygray        Everyday Grey
wintermute:facenoir            Face Noir
wintermute:findinghope         Finding Hope
wintermute:forgottensound1     Forgotten Sound 1 - Revelation
wintermute:forgottensound2     Forgotten Sound 2 - Destiny
wintermute:four                Four
wintermute:foxtail             FoxTail
wintermute:framed              Framed
wintermute:fred                Fred
wintermute:ghostsheet          Ghost in the Sheet
wintermute:goldencalf          The Golden Calf
wintermute:guttenburg          The Guttenburg Project
wintermute:hamlet              Hamlet or the last game without MMORPG features, shaders and product placement
wintermute:helga               Helga Deep In Trouble
wintermute:hor                 Hor
wintermute:idiotstale          The Idiot's Tale
wintermute:imustkill           I Must Kill...: Fresh Meat
wintermute:jamesperis          James Peris: No License Nor Control
wintermute:klaymen1            Klaymen Episodes: Pilot
wintermute:knossos             K'NOSSOS
wintermute:kulivocko           Kulivocko
wintermute:lifein3minutes      Life In 3 Minutes
wintermute:lonelyrobot         Project Lonely Robot
wintermute:looky               Looky
wintermute:lovmamuta           Lov Mamuta
wintermute:julia               J.U.L.I.A.
wintermute:juliastars          J.U.L.I.A.: Among the Stars
wintermute:juliauntold         J.U.L.I.A.: Untold
wintermute:lotl                Limbo of the Lost
wintermute:machumayu           Machu Mayu
wintermute:mentalrepairs       Mental Repairs Inc
wintermute:mirage              Mirage
wintermute:miskatonic1         Miskatonic. Part One
wintermute:msos                Monday Starts on Saturday
wintermute:mukhtar             Mukhtar and his Team
wintermute:mystictriddle       Mystic Triddle
wintermute:mythguff            Myth: A Guff's Tale
wintermute:nightinthefog       Night in the Fog
wintermute:nighttrain          Night Train
wintermute:nosebound1          Nose Bound: Episode 1
wintermute:octave              Octave
wintermute:oknytt              Oknytt
wintermute:one                 One
wintermute:onehelluvaday       One Helluva Day
wintermute:openquest           Open Quest
wintermute:paintaria           Paintaria
wintermute:palladion           Palladion
wintermute:papasdaughters1     Papa's Daughters
wintermute:papasdaughters2     Papa's Daughters Go to the Sea
wintermute:petka02             Red Comrades 0.2: Operation F.
wintermute:pigeons             Pigeons in the Park
wintermute:pizzamorgana        Pizza Morgana: Episode 1 - Monsters and Manipulations in the Magical Forest
wintermute:polechudes          Pole Chudes
wintermute:preciouspills       Precious Pills, Blasting Bacon and Mowing Minds
wintermute:projectdoom         Project: Doom
wintermute:projectjoe          Project Joe
wintermute:qajarycat           Qajary Cat
wintermute:rebeccacarlson1     Rebecca Carlson Mystery 01 - Silent Footsteps
wintermute:reptilesquest       On the Tracks of Dinosaurs
wintermute:reversion1          Reversion: The Escape
wintermute:reversion2          Reversion: The Meeting
wintermute:reversion3          Reversion: The Return
wintermute:rhiannon            Rhiannon: Curse of the four Branches
wintermute:ritter              1 1/2 Ritter: Auf der Suche nach der hinreissenden Herzelinde
wintermute:rosemary            Rosemary
wintermute:royalmahjong        Royal Mahjong: King's Journey
wintermute:satanandsons        Satan and Sons
wintermute:securanote          Securanote
wintermute:shaban              Shaban
wintermute:shadowofnebula      Shadow Of Nebula
wintermute:shelter             Shelter
wintermute:shinestar           The Shine of a Star
wintermute:spaceinvaders       Space Invaders
wintermute:spacemadness        Space Madness
wintermute:sof1                Stroke of Fate: Operation Valkyrie
wintermute:sof2                Stroke of Fate: Operation Bunker
wintermute:sofiasdebt          Sofia's Debt
wintermute:sotv1               Shadows on the Vatican - Act I: Greed
wintermute:sotv2               Shadows on the Vatican - Act II: Wrath
wintermute:strangechange       Strange Change
wintermute:sunny               Sunny
wintermute:sunrise             Sunrise: The game
wintermute:susanrose1          Susan Rose: Mysterious Child
wintermute:susanrose2          Susan Rose: Delicate Murder
wintermute:tanya1              Tanya Grotter and the Magical Double Bass
wintermute:tanya2              Tanya Grotter and the Disappearing Floor
wintermute:tehran1933          Murder In Tehran's Alleys 1933
wintermute:tehran2016          Murder In Tehran's Alleys 2016
wintermute:theancientmark1     The Ancient Mark - Episode 1
wintermute:tetriks             TeTRIks
wintermute:thebox              The Box
wintermute:thekite             The Kite
wintermute:thelastcrownmh      The Last Crown - Midnight Horror
wintermute:thelostcrowngha     The Lost Crown - A Ghost-Hunting Adventure
wintermute:tib                 Fairy Tales About Toshechka and Boshechka
wintermute:todaymama           Today, Mama!
wintermute:tradestory          The Trader of Stories
wintermute:twc                 The White Chamber
wintermute:war                 War
wintermute:vsevolod            Vsevolod
wintermute:wayoflove           The Way Of Love: Sub Zero
wintermute:wintermute          Wintermute engine game
wintermute:wmedemo             Wintermute Engine Technology Demo
wintermute:wmedemo3d           Wintermute 3D Characters Technology Demo
wintermute:wtetris             Wilma Tetris
wintermute:zilm                Zilm: A Game of Reflex
wintermute:zbang               Zbang! The Game
xeen:cloudsofxeen              Might and Magic IV: Clouds of Xeen
xeen:darksideofxeen            Might and Magic V: Darkside of Xeen
xeen:worldofxeen               Might and Magic: World of Xeen
xeen:swordsofxeen              Might and Magic: Swords of Xeen
zvision:znemesis               Zork Nemesis: The Forbidden Lands
zvision:zgi                    Zork: Grand Inquisitor

