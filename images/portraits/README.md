# Fighter portraits

Portraits are looked up by gang, then by fighter type, in the `PORTRAITS` map near the
top of the script in `index.html`. All 125 fighter types across the 16 gangs already have
an entry pointing at the path below, so adding art is only a matter of dropping a
correctly named file into place — no code change needed.

Anything missing falls back to the tinted placeholder frame, so partial coverage is
fine and a wrong filename shows the frame rather than a broken image. A portrait set
on an individual fighter in the app always overrides the type art here.

## Naming

Folder and file prefix are the gang name without a leading "House" or "The":
`house-goliath` becomes `goliath`, `Ash Waste Nomads` stays `ash-waste-nomads`.
The paths in the table below are the ones the app looks for — copy them exactly.

## Format

150x200 PNG, model centred, plain light background. The card crops to about 3:4
anchored near the top, so keep the head clear of the top edge. These are referenced
by path and never copied into a saved roster, so they cost nothing in storage or sync.

## Status

19 of 125 done (106 to go).

| Gang | Fighter | Role | File | Have |
|---|---|---|---|---|
| Ash Waste Nomads | Ash Waste Nomad Chieftain | Leader | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-chieftain.png` | x |
| Ash Waste Nomads | Ash Waste Nomad Watcher | Champion | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-watcher.png` | x |
| Ash Waste Nomads | Ash Waste Nomad Stormcaller | Champion | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-stormcaller.png` | x |
| Ash Waste Nomads | Ash Waste Nomad Warrior | Ganger | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-warrior.png` | x |
| Ash Waste Nomads | Ash Waste Nomad Hunter | Prospect | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-hunter.png` | x |
| Ash Waste Nomads | Ash Waste Nomad Dust Runner | Prospect | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-dust-runner.png` | x |
| Ash Waste Nomads | Arthromite Duneskuttler | Brute | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-duneskuttler.png` | x |
| Ash Waste Nomads | Arthromite Spinewyrm | Pet | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-arthromite-spinewyrm.png` | x |
| Ash Waste Nomads | Unbound Helamite | Pet | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-unbound-helamite.png` | x |
| Ash Waste Nomads | Ashwing Helamite | Pet | `images/portraits/ash-waste-nomads/portrait-ash-waste-nomads-ashwing-helamite.png` | x |
| Chaos Helot Cult | Chaos Helot Cult Demagogue | Leader | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-demagogue.png` |  |
| Chaos Helot Cult | Chaos Helot Cult Disciple | Champion | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-disciple.png` |  |
| Chaos Helot Cult | Chaos Helot Cult Witch | Champion | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-witch.png` |  |
| Chaos Helot Cult | Chaos Helot Cultist | Ganger | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-cultist.png` |  |
| Chaos Helot Cult | Chaos Helot Initiate | Prospect | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-initiate.png` |  |
| Chaos Helot Cult | Chaos Spawn | Brute | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-spawn.png` |  |
| Chaos Helot Cult | Chaos Familiar | Pet | `images/portraits/chaos-helot-cult/portrait-chaos-helot-cult-familiar.png` |  |
| Corpse Grinder Cult | Corpse Grinder Cult Butcher | Leader | `images/portraits/corpse-grinder-cult/portrait-corpse-grinder-cult-butcher.png` |  |
| Corpse Grinder Cult | Corpse Grinder Cult Cutter | Champion | `images/portraits/corpse-grinder-cult/portrait-corpse-grinder-cult-cutter.png` |  |
| Corpse Grinder Cult | Corpse Grinder Cult Skinner | Ganger | `images/portraits/corpse-grinder-cult/portrait-corpse-grinder-cult-skinner.png` |  |
| Corpse Grinder Cult | Corpse Grinder Cult Initiate | Prospect | `images/portraits/corpse-grinder-cult/portrait-corpse-grinder-cult-initiate.png` |  |
| Corpse Grinder Cult | Chaos Spawn | Brute | `images/portraits/corpse-grinder-cult/portrait-corpse-grinder-cult-chaos-spawn.png` |  |
| Free Ogryns | Ogryn Overboss | Leader | `images/portraits/free-ogryns/portrait-free-ogryns-ogryn-overboss.png` |  |
| Free Ogryns | Ogryn Underboss | Champion | `images/portraits/free-ogryns/portrait-free-ogryns-ogryn-underboss.png` |  |
| Free Ogryns | Stevedore Ogryn | Ganger | `images/portraits/free-ogryns/portrait-free-ogryns-stevedore-ogryn.png` |  |
| Free Ogryns | Lobo Ogryn | Prospect | `images/portraits/free-ogryns/portrait-free-ogryns-lobo-ogryn.png` |  |
| Genestealer Cults | Genestealer Cult Adept | Leader | `images/portraits/genestealer-cults/portrait-genestealer-cults-adept.png` |  |
| Genestealer Cults | Genestealer Cult Alpha | Leader | `images/portraits/genestealer-cults/portrait-genestealer-cults-alpha.png` |  |
| Genestealer Cults | Genestealer Cult Hybrid Acolyte | Champion | `images/portraits/genestealer-cults/portrait-genestealer-cults-hybrid-acolyte.png` |  |
| Genestealer Cults | Genestealer Cult Neophyte Hybrid | Ganger | `images/portraits/genestealer-cults/portrait-genestealer-cults-neophyte-hybrid.png` |  |
| Genestealer Cults | Genestealer Cult Aberrant | Ganger | `images/portraits/genestealer-cults/portrait-genestealer-cults-aberrant.png` |  |
| Genestealer Cults | Genestealer Cult Hybrid Initiate | Prospect | `images/portraits/genestealer-cults/portrait-genestealer-cults-hybrid-initiate.png` |  |
| Genestealer Cults | Genestealer Cult Abominant | Brute | `images/portraits/genestealer-cults/portrait-genestealer-cults-abominant.png` |  |
| Genestealer Cults | Psychic Familiar | Pet | `images/portraits/genestealer-cults/portrait-genestealer-cults-psychic-familiar.png` |  |
| House Cawdor | Cawdor Word-Keeper | Leader | `images/portraits/cawdor/portrait-cawdor-word-keeper.png` |  |
| House Cawdor | Cawdor Firebrand | Champion | `images/portraits/cawdor/portrait-cawdor-firebrand.png` |  |
| House Cawdor | Cawdor Brethren | Ganger | `images/portraits/cawdor/portrait-cawdor-brethren.png` |  |
| House Cawdor | Cawdor Way-Brethren | Prospect | `images/portraits/cawdor/portrait-cawdor-way-brethren.png` |  |
| House Cawdor | Cawdor Bonepicker | Prospect | `images/portraits/cawdor/portrait-cawdor-bonepicker.png` |  |
| House Cawdor | Cawdor Stig-Shambler | Brute | `images/portraits/cawdor/portrait-cawdor-stig-shambler.png` |  |
| House Cawdor | Redemptionist Priest | Leader | `images/portraits/cawdor/portrait-cawdor-redemptionist-priest.png` |  |
| House Cawdor | Redemptionist Deacon | Champion | `images/portraits/cawdor/portrait-cawdor-redemptionist-deacon.png` |  |
| House Cawdor | Redemptionist Brethren | Ganger | `images/portraits/cawdor/portrait-cawdor-redemptionist-brethren.png` |  |
| House Cawdor | Redemptionist Zealot | Prospect | `images/portraits/cawdor/portrait-cawdor-redemptionist-zealot.png` |  |
| House Cawdor | Sheen Bird | Pet | `images/portraits/cawdor/portrait-cawdor-sheen-bird.png` |  |
| House Delaque | Delaque Master of Shadow | Leader | `images/portraits/delaque/portrait-delaque-master-of-shadow.png` |  |
| House Delaque | Delaque Phantom | Champion | `images/portraits/delaque/portrait-delaque-phantom.png` |  |
| House Delaque | Delaque Nacht-Ghul | Champion | `images/portraits/delaque/portrait-delaque-nacht-ghul.png` |  |
| House Delaque | Delaque Ghost | Ganger | `images/portraits/delaque/portrait-delaque-ghost.png` |  |
| House Delaque | Delaque Psy-Gheist | Prospect | `images/portraits/delaque/portrait-delaque-psy-gheist.png` |  |
| House Delaque | Delaque Shadow | Prospect | `images/portraits/delaque/portrait-delaque-shadow.png` |  |
| House Delaque | Piscean Spektor | Brute | `images/portraits/delaque/portrait-delaque-piscean-spektor.png` |  |
| House Delaque | Cephalopod Spektor | Pet | `images/portraits/delaque/portrait-delaque-cephalopod-spektor.png` |  |
| House Delaque | Psychoteric Wyrm | Pet | `images/portraits/delaque/portrait-delaque-psychoteric-wyrm.png` |  |
| House Escher | Escher Gang Queen | Leader | `images/portraits/escher/portrait-escher-gang-queen.png` | x |
| House Escher | Escher Gang Matriarch | Champion | `images/portraits/escher/portrait-escher-matriarch.png` | x |
| House Escher | Escher Death-Maiden | Champion | `images/portraits/escher/portrait-escher-death-maiden.png` | x |
| House Escher | Escher Gang Sister | Ganger | `images/portraits/escher/portrait-escher-ganger.png` | x |
| House Escher | Escher Wyld Runner | Prospect | `images/portraits/escher/portrait-escher-wyld-runner.png` | x |
| House Escher | Escher Little Sister | Prospect | `images/portraits/escher/portrait-escher-little-sister.png` | x |
| House Escher | Khimerix | Brute | `images/portraits/escher/portrait-escher-khimerix.png` | x |
| House Escher | Phyrr Cat | Pet | `images/portraits/escher/portrait-escher-phyrr-cat.png` | x |
| House Escher | Phelynx | Pet | `images/portraits/escher/portrait-escher-phelynx.png` | x |
| House Goliath | Goliath Forge Tyrant | Leader | `images/portraits/goliath/portrait-goliath-forge-tyrant.png` |  |
| House Goliath | Goliath Forge Boss | Champion | `images/portraits/goliath/portrait-goliath-forge-boss.png` |  |
| House Goliath | Goliath Stimmer | Champion | `images/portraits/goliath/portrait-goliath-stimmer.png` |  |
| House Goliath | Goliath Bruiser | Ganger | `images/portraits/goliath/portrait-goliath-bruiser.png` |  |
| House Goliath | Goliath Forge-Born | Prospect | `images/portraits/goliath/portrait-goliath-forge-born.png` |  |
| House Goliath | Goliath Bully | Prospect | `images/portraits/goliath/portrait-goliath-bully.png` |  |
| House Goliath | Goliath 'Zerker | Brute | `images/portraits/goliath/portrait-goliath-zerker.png` |  |
| House Goliath | Sumpkroc | Pet | `images/portraits/goliath/portrait-goliath-sumpkroc.png` |  |
| House Orlock | Orlock Road Captain | Leader | `images/portraits/orlock/portrait-orlock-road-captain.png` |  |
| House Orlock | Orlock Road Sergeant | Champion | `images/portraits/orlock/portrait-orlock-road-sergeant.png` |  |
| House Orlock | Orlock Arms Master | Champion | `images/portraits/orlock/portrait-orlock-arms-master.png` |  |
| House Orlock | Orlock Gunner | Ganger | `images/portraits/orlock/portrait-orlock-gunner.png` |  |
| House Orlock | Orlock Wrecker | Prospect | `images/portraits/orlock/portrait-orlock-wrecker.png` |  |
| House Orlock | Orlock Greenhorn | Prospect | `images/portraits/orlock/portrait-orlock-greenhorn.png` |  |
| House Orlock | Cyber-Mastiff | Pet | `images/portraits/orlock/portrait-orlock-cyber-mastiff.png` |  |
| House Van Saar | Van Saar Prime | Leader | `images/portraits/van-saar/portrait-van-saar-prime.png` |  |
| House Van Saar | Van Saar Augmek | Champion | `images/portraits/van-saar/portrait-van-saar-augmek.png` |  |
| House Van Saar | Van Saar Archeotek | Champion | `images/portraits/van-saar/portrait-van-saar-archeotek.png` |  |
| House Van Saar | Van Saar Tek | Ganger | `images/portraits/van-saar/portrait-van-saar-tek.png` |  |
| House Van Saar | Van Saar Neotek | Prospect | `images/portraits/van-saar/portrait-van-saar-neotek.png` |  |
| House Van Saar | Van Saar Subtek | Prospect | `images/portraits/van-saar/portrait-van-saar-subtek.png` |  |
| House Van Saar | Van Saar Ash Wastes 'Arachni-Rig' | Vehicle | `images/portraits/van-saar/portrait-van-saar-ash-wastes-arachni-rig.png` |  |
| House Van Saar | Cyberachnid | Pet | `images/portraits/van-saar/portrait-van-saar-cyberachnid.png` |  |
| Outcasts | Outcast Leader | Leader | `images/portraits/outcasts/portrait-outcasts-leader.png` |  |
| Outcasts | Outcast Champion | Champion | `images/portraits/outcasts/portrait-outcasts-champion.png` |  |
| Outcasts | Outcast Hive Scum | Ganger | `images/portraits/outcasts/portrait-outcasts-hive-scum.png` |  |
| Palanite Enforcers | Enforcer Captain | Leader | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-captain.png` |  |
| Palanite Enforcers | Enforcer Sergeant | Champion | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-sergeant.png` |  |
| Palanite Enforcers | Enforcer Subjugator Sergeant | Champion | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-subjugator-sergeant.png` |  |
| Palanite Enforcers | Enforcer Patrol Officer | Ganger | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-patrol-officer.png` |  |
| Palanite Enforcers | Enforcer Subjugator Patrol Officer | Ganger | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-subjugator-patrol-officer.png` |  |
| Palanite Enforcers | Enforcer Rookie | Prospect | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-rookie.png` |  |
| Palanite Enforcers | Enforcer Haunt | Prospect | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-haunt.png` |  |
| Palanite Enforcers | Enforcer 'Sanctioner' Pattern Automata | Brute | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-sanctioner-pattern-automata.png` |  |
| Palanite Enforcers | Enforcer Tauros Venator | Vehicle | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-enforcer-tauros-venator.png` |  |
| Palanite Enforcers | Hardcase Cyber-Mastiff | Pet | `images/portraits/palanite-enforcers/portrait-palanite-enforcers-hardcase-cyber-mastiff.png` |  |
| Spyre Hunting Party | Spyre Hunt Master | Leader | `images/portraits/spyre-hunting-party/portrait-spyre-hunting-party-hunt-master.png` |  |
| Spyre Hunting Party | Jakara Spyre Hunter | Champion | `images/portraits/spyre-hunting-party/portrait-spyre-hunting-party-jakara-spyre-hunter.png` |  |
| Spyre Hunting Party | Malcadon Spyre Hunter | Champion | `images/portraits/spyre-hunting-party/portrait-spyre-hunting-party-malcadon-spyre-hunter.png` |  |
| Spyre Hunting Party | Orrus Spyre Hunter | Champion | `images/portraits/spyre-hunting-party/portrait-spyre-hunting-party-orrus-spyre-hunter.png` |  |
| Spyre Hunting Party | Yeld Spyre Hunter | Champion | `images/portraits/spyre-hunting-party/portrait-spyre-hunting-party-yeld-spyre-hunter.png` |  |
| Spyre Hunting Party | Caryatid Prime | Pet | `images/portraits/spyre-hunting-party/portrait-spyre-hunting-party-caryatid-prime.png` |  |
| The Malstrain | Malstrain Alpha | Leader | `images/portraits/malstrain/portrait-malstrain-alpha.png` |  |
| The Malstrain | Malstrain Genestealer | Champion | `images/portraits/malstrain/portrait-malstrain-genestealer.png` |  |
| The Malstrain | Malstrain Coalescence | Champion | `images/portraits/malstrain/portrait-malstrain-coalescence.png` |  |
| The Malstrain | Malstrain Brood Scum | Ganger | `images/portraits/malstrain/portrait-malstrain-brood-scum.png` |  |
| The Malstrain | Malstrain Tyramite | Pet | `images/portraits/malstrain/portrait-malstrain-tyramite.png` |  |
| Venators | House Hunt Leader | Leader | `images/portraits/venators/portrait-venators-house-hunt-leader.png` |  |
| Venators | Ogryn Hunt Leader | Leader | `images/portraits/venators/portrait-venators-ogryn-hunt-leader.png` |  |
| Venators | Squat Hunt Leader | Leader | `images/portraits/venators/portrait-venators-squat-hunt-leader.png` |  |
| Venators | Ratling Hunt Leader | Leader | `images/portraits/venators/portrait-venators-ratling-hunt-leader.png` |  |
| Venators | Beastman Hunt Leader | Leader | `images/portraits/venators/portrait-venators-beastman-hunt-leader.png` |  |
| Venators | House Hunt Champion | Champion | `images/portraits/venators/portrait-venators-house-hunt-champion.png` |  |
| Venators | Ogryn Hunt Champion | Champion | `images/portraits/venators/portrait-venators-ogryn-hunt-champion.png` |  |
| Venators | Squat Hunt Champion | Champion | `images/portraits/venators/portrait-venators-squat-hunt-champion.png` |  |
| Venators | Ratling Hunt Champion | Champion | `images/portraits/venators/portrait-venators-ratling-hunt-champion.png` |  |
| Venators | Beastman Hunt Champion | Champion | `images/portraits/venators/portrait-venators-beastman-hunt-champion.png` |  |
| Venators | House Hunter | Ganger | `images/portraits/venators/portrait-venators-house-hunter.png` |  |
| Venators | Ogryn Hunter | Ganger | `images/portraits/venators/portrait-venators-ogryn-hunter.png` |  |
| Venators | Squat Hunter | Ganger | `images/portraits/venators/portrait-venators-squat-hunter.png` |  |
| Venators | Ratling Hunter | Ganger | `images/portraits/venators/portrait-venators-ratling-hunter.png` |  |
| Venators | Beastman Hunter | Ganger | `images/portraits/venators/portrait-venators-beastman-hunter.png` |  |
