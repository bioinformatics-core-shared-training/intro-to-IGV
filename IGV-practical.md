
# Practical Session 1 - RNA-seq and ChIP-seq data

This	session	will	give	you	short	introduction	into	using	IGV.	We	will	be	using	externally-hosted	data available	from *Encode*	including	ChIP-seq	and	RNA-seq	data. Please	feel	free	to	try	other	datasets	once	you	have	run	through	the	tasks	but	remember	IGV	is	hosted	on	your	machine	so	less	powerful	computers	will	feel	the	memory	load	of	large	numbers	of	datasets.

# RNA-seq data

## Starting a new session

- Clear data by going to IGV menu -> File -> New Session...

## Loading the data

- Go	to	the	IGV	menu	->	File	->	load	from	server
- From	the	menu	follow	drop-down
    + Tutorials	->	RNA-seq (Body	Map)
    + Heart
    + Lung
- Go	to	IGV	menu	->	Views	->	Preferences	->	Alignments
    + Tick	'show	junction	track'
    + Set	'visibility	range	threshold'	to	15kb
- Collapse	reads	track	(named	Heart/Liver)

## Inspect RNA-seq data

- Select	tracks	->	Colour	Alignments	by	->	Read	Strand	to	identify	strand	of	transcript
- Expand	"Features	track"	to	identify	alternative	exons/transcripts.
- Inspect	coverage	tracks	to	discover	areas	of	coverage	unique	to	Heart	or	
Liver	sample.
- Inspect	junction	tracks	to evaluate	alternative	splicing	of	transcripts	
between	tissue
- Select	junction	tracks	->	Expand
- Compare	major	(first)	transcript	variant	in	Heart	and	Tissue
- Click	on	junctions	to	identify	start	and	end	of	spans.

## Another way to inspect splicing

- Select	tracks	->	Shashmi	plot
    + Select	Gene	Track	->	Refseq	Genes
    + Select	Alignment	Tracks	–>	Heart		+	Liver
- Save image and compare junctions across tissue

# ChIP-seq data
This	section	looks	at	how	to	load	and	manipulate	some	ChIP-seq	data.	The	data	is	
from	a	lymphoblastoma	cell	line	and	contains	ChIP-seq	samples	for	several	
histone	types.

## Loading IGV and moving around the gene of interest

- First, load IGV and select the *hg19* genome.
- Navigate	to `chr12:6,641,585-6,649,537`.
- Navigate	to	**Gapdh**.

v 
v Zoom	out	to	see	the	surrounding	genes.
v Select	the	“RefSeq	Genes”	track	and	expand	to	see	all	transcript	isoforms.	
v Scroll	to	the	left	to	discover	the	non-coding	RNA	SCRNA2.	
v Click	on	SCRNA	to	bring	up	a	window	with	further	information.
v Double	click	on	Gapdh	to	recentre	window	on	the	gene.
v Add	a	region	of	interest	at	the	Gapdh	locus	using	the	IGV	menu
Regions	->	Region	Navigator	->	add
v Right	click	the	“Region	of interest”	and	edit	description	to	show	“Active	
gene”
