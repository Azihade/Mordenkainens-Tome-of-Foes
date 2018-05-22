var iFileName = "MToF.js";
RequiredSheetVersion(12.999);
// This file adds the content from the Mordenkainen's Tome of Foes to MPMB's Character Record Sheet

// Define the source
SourceList["MTF"] = {
	name : "Mordenkainen's Tome of Foes",
	abbreviation : "MTF",
};

// Much of this code was contributed by Friedrich
RaceList["baalzebul tiefling"] = {
	regExpSearch : /^(?=.*baalzebul)(?=.*tiefling|planetouched).*$/i,
	name : "Baalzebul tiefling",
	sortname : "Tiefling, Baalzebul",
	source : ["MTF", 21],
	plural : "Baalzebul tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Baalzebul Tiefling: +1 Intelligence, +2 Charisma;",
	scores : [0, 0, 0, 1, 0, 2],
	trait : "Baalzebul Tiefling (+1 Intelligence, +2 Charisma)\n\nLegacy of Maladomini:\n   I know the Thaumaturgy cantrip.\n   At 3rd level, I can cast the Ray of Sickness spell once per long rest as a 2nd-level spell.\n   At 5th level, I can also cast the Crown of Madness spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Maladomini (1)",
		spells : ["thaumaturgy"],
		selection : ["thaumaturgy"],
		atwill : true
	},
	features : {
		"ray of sickness" : {
			name : "Ray of Sickness",
			minlevel : 3,
			usages : 1,
			additional : "3d8",
			recovery : "long rest",
			tooltip : " (Legacy of Maladomini)",
			action : ["action", " (3d8)"],
			spellcastingBonus : {
				name : "Legacy of Maladomini (3)",
				spells : ["ray of sickness"],
				selection : ["ray of sickness"],
				oncelr : true
			}
		},
		"crown of madness" : {
			name : "Crown of Madness",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Maladomini)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Maladomini (5)",
				spells : ["crown of madness"],
				selection : ["crown of madness"],
				oncelr : true
			}
		}
	}
};
RaceList["dispater tiefling"] = {
	regExpSearch : /^(?=.*dispater)(?=.*tiefling|planetouched).*$/i,
	name : "Dispater tiefling",
	sortname : "Tiefling, Dispater",
	source : ["MTF", 21],
	plural : "Dispater tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Dispater Tiefling: +1 Dexterity, +2 Charisma;",
	scores : [0, 1, 0, 0, 0, 2],
	trait : "Dispater Tiefling (+1 Dexterity, +2 Charisma)\n\nLegacy of Dis:\n   I know the Thaumaturgy cantrip.\n   At 3rd level, I can cast the Disguise Self spell once per long rest.\n   At 5th level, I can also cast the Detect Thoughts spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Dis (level 1)",
		spells : ["thaumaturgy"],
		selection : ["thaumaturgy"],
		atwill : true
	},
	features : {
		"disguise self" : {
			name : "Disguise Self",
			minlevel : 3,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Dis)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Dis (level 3)",
				spells : ["disguise self"],
				selection : ["disguise self"],
				oncelr : true
			}
		},
		"detect thoughts" : {
			name : "Detect Thoughts",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Dis)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Dis (level 5)",
				spells : ["detect thoughts"],
				selection : ["detect thoughts"],
				oncelr : true
			}
		}
	}
};
RaceList["fierna tiefling"] = {
	regExpSearch : /^(?=.*fierna)(?=.*tiefling|planetouched).*$/i,
	name : "Fierna tiefling",
	sortname : "Tiefling, Fierna",
	source : ["MTF", 21],
	plural : "Fierna tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Fierna Tiefling: +1 Wisdom, +2 Charisma;",
	scores : [0, 0, 0, 0, 1, 2],
	trait : "Fierna Tiefling (+1 Wisdom, +2 Charisma)\n\nLegacy of Phlegethos:\n   I know the Friends cantrip.\n   At 3rd level, I can cast the Charm Person spell once per long rest as a 2nd-level spell.\n   At 5th level, I can also cast the Suggestion spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Phlegethos (1)",
		spells : ["friends"],
		selection : ["friends"],
		atwill : true
	},
	features : {
		"charm person" : {
			name : "Charm Person",
			minlevel : 3,
			usages : 1,
			additional : "2 targets",
			recovery : "long rest",
			tooltip : " (Legacy of Phlegethos)",
			action : ["action", " (2 targets)"],
			spellcastingBonus : {
				name : "Legacy of Phlegethos (3)",
				spells : ["charm person"],
				selection : ["charm person"],
				oncelr : true
			}
		},
		"suggestion" : {
			name : "Suggestion",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Phlegethos)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Phlegethos (5)",
				spells : ["suggestion"],
				selection : ["suggestion"],
				oncelr : true
			}
		}
	}
};
RaceList["glasya tiefling"] = {
	regExpSearch : /^(?=.*glasya)(?=.*tiefling|planetouched).*$/i,
	name : "Glasya tiefling",
	sortname : "Tiefling, Glasya",
	source : ["MTF", 22],
	plural : "Glasya tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Glasya Tiefling: +1 Dexterity, +2 Charisma;",
	scores : [0, 1, 0, 0, 0, 2],
	trait : "Glasya Tiefling (+1 Dexterity, +2 Charisma)\n\nLegacy of Malbolge:\n   I know the Minor Illusion cantrip.\n   At 3rd level, I can cast the Disguise Self spell once per long rest.\n   At 5th level, I can also cast the Invisibility spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Malbolge (1)",
		spells : ["minor illusion"],
		selection : ["minor illusion"],
		atwill : true
	},
	features : {
		"disguise self" : {
			name : "Disguise Self",
			minlevel : 3,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Malbolge)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Malbolge (3)",
				spells : ["disguise self"],
				selection : ["disguise self"],
				oncelr : true
			}
		},
		"invisibility" : {
			name : "Invisibility",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Malbolge)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Malbolge (5)",
				spells : ["invisibility"],
				selection : ["invisibility"],
				oncelr : true
			}
		}
	}
};
RaceList["levistus tiefling"] = {
	regExpSearch : /^(?=.*levistus)(?=.*tiefling|planetouched).*$/i,
	name : "Levistus tiefling",
	sortname : "Tiefling, Levistas",
	source : ["MTF", 22],
	plural : "Levistus tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Levistas Tiefling: +1 Constitution, +2 Charisma;",
	scores : [0, 0, 1, 0, 0, 2],
	trait : "Levistas Tiefling (+1 Constitution, +2 Charisma)\n\nLegacy of Stygia:\n   I know the Ray of Frost cantrip.\n   At 3rd level, I can cast the Armor of Agathys spell once per long rest as a 2nd-level spell.\n   At 5th level, I can also cast the Darkness spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Stygia (1)",
		spells : ["ray of frost"],
		selection : ["ray of frost"],
		atwill : true
	},
	features : {
		"armor of agathys" : {
			name : "Armor of Agathys",
			minlevel : 3,
			usages : 1,
			additional : "2nd-level",
			recovery : "long rest",
			tooltip : " (Legacy of Stygia)",
			action : ["action", " (2nd-level)"],
			spellcastingBonus : {
				name : "Legacy of Stygia (3)",
				spells : ["armor of agathys"],
				selection : ["armor of agathys"],
				oncelr : true
			}
		},
		"darkness" : {
			name : "Darkness",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Stygia)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Stygia (5)",
				spells : ["darkness"],
				selection : ["darkness"],
				oncelr : true
			}
		}
	}
};
RaceList["mammon tiefling"] = {
	regExpSearch : /^(?=.*mammon)(?=.*tiefling|planetouched).*$/i,
	name : "Mammon tiefling",
	sortname : "Tiefling, Mammon",
	source : ["MTF", 22],
	plural : "Mammon tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Mammon Tiefling: +1 Intelligence, +2 Charisma;",
	scores : [0, 0, 0, 1, 0, 2],
	trait : "Mammon Tiefling (+1 Intelligence, +2 Charisma)\nLegacy of Minauros:\n   I know the Mage Hand cantrip.\n   At 3rd level, I can cast the Tenster's Floating Disk spell once per short rest.\n   At 5th level, I can also cast the Arcane Lock spell wihtout a material component once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Minauros (1)",
		spells : ["mage hand"],
		selection : ["mage hand"],
		atwill : true
	},
	features : {
		"tenser's floating disk" : {
			name : "Tenser's Floating Disk",
			minlevel : 3,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Minauros)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Minauros (3)",
				spells : ["tenser's floating disk"],
				selection : ["tenser's floating disk"],
				oncesr : true
			}
		},
		"arcane lock" : {
			name : "Arcane Lock",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Minauros)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Minauros (5)",
				spells : ["arcane lock"],
				selection : ["arcane lock"],
				oncelr : true
			}
		}
	}
};
RaceList["mephistopheles tiefling"] = {
	regExpSearch : /^(?=.*mephistopheles)(?=.*tiefling|planetouched).*$/i,
	name : "Mephistopheles tiefling",
	sortname : "Tiefling, Mephistopheles",
	source : ["MTF", 23],
	plural : "Mephistopheles tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Mephistopheles Tiefling: +1 Intelligence, +2 Charisma;",
	scores : [0, 0, 0, 1, 0, 2],
	trait : "Mephistopheles Tiefling (+1 Intelligence, +2 Charisma)\n\nLegacy of Cania:\n   I know the Mage Hand cantrip.\n   At 3rd level, I can cast the Burning Hands spell once per long rest as a 2nd-level spell.\n   At 5th level, I can also cast the Flame Blade spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Cania (level 1)",
		spells : ["mage hand"],
		selection : ["mage hand"],
		atwill : true
	},
	features : {
		"burning hands" : {
			name : "Burning Hands",
			minlevel : 3,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Cania)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Cania (level 3)",
				spells : ["burning hands"],
				selection : ["burning hands"],
				oncelr : true
			}
		},
		"flame blade" : {
			name : "Flame Blade",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Cania)",
			action : ["action", ""],
			spellcastingBonus : {
				name : "Legacy of Cania (level 5)",
				spells : ["fllame blade"],
				selection : ["blade"],
				oncelr : true
			}
		}
	}
};
RaceList["zariel tiefling"] = {
	regExpSearch : /^(?=.*zariel)(?=.*tiefling|planetouched).*$/i,
	name : "Zariel tiefling",
	sortname : "Tiefling, Zariel",
	source : ["MTF", 23],
	plural : "Zariel tieflings",
	size : 3,
	speed : {
		walk : { spd : 30, enc : 20 }
	},
	languageProfs : ["Common", "Infernal"],
	vision : [["Darkvision", 60]],
	dmgres : ["Fire"],
	age : " reach adulthood in their late teens and live around 100 years",
	height : " range from 5 to over 6 feet tall (4'9\" + 2d8\")",
	weight : " weigh around 155 lb (110 + 2d8 \xD7 2d4 lb)",
	heightMetric : " range from 1,5 to over 1,8 metres tall (145 + 5d8 cm)",
	weightMetric : " weigh around 70 kg (50 + 5d8 \xD7 4d4 / 10 kg)",
	improvements : "Zariel Tiefling: +1 Strength, +2 Charisma;",
	scores : [1, 0, 0, 0, 0, 2],
	trait : "Zariel Tiefling (+1 Strength, +2 Charisma)\n\nLegacy of Avernus:\n   I know the Thaumaturgy cantrip.\n   At 3rd level, I can cast the Searing Smite spell once per long rest as a 2nd-level spell.\n   At 5th level, I can also cast the Web spell once per long rest.\n   Charisma is my spellcasting ability for these spells.",
	abilitySave : 6,
	spellcastingAbility : 6,
	spellcastingBonus : {
		name : "Legacy of Avernus (1)",
		spells : ["thaumaturgy"],
		selection : ["thaumaturgy"],
		atwill : true
	},
	features : {
		"searing smite" : {
			name : "Searing Smite",
			additional : "2d6",
			minlevel : 3,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Avernus)",
			action : ["bonus action", " (2d6)"],
			spellcastingBonus : {
				name : "Legacy of Avernus (3)",
				spells : ["searing smite"],
				selection : ["searing smite"],
				oncelr : true
			}
		},
		"branding smite" : {
			name : "Branding Smite",
			minlevel : 5,
			usages : 1,
			recovery : "long rest",
			tooltip : " (Legacy of Avernus)",
			action : ["bonus action", ""],
			spellcastingBonus : {
				name : "Legacy of Avernus (5)",
				spells : ["branding smite"],
				selection : ["branding smite"],
				oncelr : true
			}
		}
	}
};
