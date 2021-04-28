# The components of the system unit
**Objective**
1. Differentiate among various styles of system units
2. identify chips, adapter cards, and other components of a motherboard
3. Describe the components of a processor and how they complete a machine cycle
4. Identify the characteristics of various PC processors on the market today
5. Define a bit and decribe how a series of bits represent data
	* bit
	* byte
	* coding system
6. Differentiate among the various types of memory
7. Describe the purpose and types of expansion slots and adapter cards
8. Differentiate bewtween a port and a connector, and explain the diffence among the ports found  on PCs
9. Describe the types of buses in a computer
10. Explain the purpose of a power supply and describe how it keeps cool

## The system unit

The system unit is a case that contains electronic components of the computer used to process data

* desktop
	* Storage is part of the sys unit
* Laptop
	* Keyboard and pointing device are on top of the sys unit
* MP3, smartphones
	* input and displays are built inot the system unit
* Game consoles
	* Xbox
		* input and output are not part of the sys unit

**Desktop**
The sustem unit inisde of a desktop includes:
1. Drive bay
2. power supply
3. sound card
4. video card
5. processor
6. memory

![](http://www.carnegiecyberacademy.com/images/facultyPages/computer/computer_cross-section.gif)

### Motherboard
* The main circuit board in the system unit
* It contains:
	*  adapter cards
		* provide functions not built into the motherboard
	* processor chips
	* memory chips
* It is also called system board
![](https://i.pinimg.com/originals/3c/34/20/3c342046c8039a2e0e56536a9213356c.jpg)

### Chip
* A small piece of semi conducting material (e.g. silicon) on which integrated circuirs are etched
	* integrated circuits (IC) contain many microscopic pathways capable of carrying electrical current
* Chips are packaged so they can be attached to a circuit board (e.g. Printed circuit board(PCB))
	* Dual inline packages (DIP) hold memory chips
		* ![](https://www.theburnin.com/wp-content/uploads/2018/10/iStock-507957206-1024x681.jpg)
	* Pin grid array (PGA) holds processor chips
		* ![](https://www.globalspec.com/ImageRepository/LearnMore/201311/chips8b74c2a3d3b543d58e6a4540e6469e25.png)

### Processor
The processor, also called the central processing unit (CPU), interprets and carries out the basic instructions that operate a computer 
* contains a control unit and an arithmetic logic unit (ALU)
	* This forms a single core
* Examples:
	* multi core processors
		* A multi core processor is a chip with 2 or more separate processors
		* Each processor on a dual-core or multicore chip generally runs at a slower clock speed, but increases overall performance
	* dual core processors
		* A dual core processor is a single chip that contains two separate processors
		* ![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Dual_Core_Generic.svg/1200px-Dual_Core_Generic.svg.png)
		* Intel core duo 
			* ![](https://www.zdnet.com/a/hub/i/2014/10/04/c156f0fc-4b76-11e4-b6a0-d4ae52e95e57/core2cpu.jpg)
				* 65 nm
				* L1 data 32kb
				* L1 code 32kb
				* L2 4MB shared between boths cpus
				* First quad cores where 2 of these in the same package
		* AMD Athlon X2
	* quad core processors

### Components of a CPU
**Control unit**
* Directs and coordinates operations in computer

**Arithmetic logic unit (ALU)**
* performs arithmetic, comparisons and logical operations
	* arithmetic = addition, subtraction etc
	* comparision = more than etc
	* logical = AND, NOR, XOR etc
![](https://computersciencewiki.org/images/1/1a/Cpu_diagram.png)

#### Machine cycle

For every instruction, a processor repeats a set of four basic operations, which comprise a machine cycle

Steps:
1. Control unit will obtain program instructions or data item from memory
2. control unit will decode
	* translate instructions into commands
3. Arithmetic logic unit (ALUI) will execute
	* carry out the command
4. Control unit will store
	* write the result to memory
![](https://www.computerhope.com/jargon/m/machine-cycle.png)

#### Pipelining
Improve a CPU's performance through pipelining
* most current personal computers support pipelining
	* Processor begins fetching a second instruction before it even completes the machine cycle for the first instruction
![](http://simplecore-ger.intel.com/techdecoded/wp-content/uploads/sites/11/figure-2-3.png)

### Registers
Temporary high speed storage area that holds data and instructions
* Data register
	* stores data while ALU computes it
	* stores result of calculation
* instruction register
	* stores instuction while it is being decoded
* instruction address register
	* stores location from where instruction was fetched
* address register

### System clock

* System clock controls the timing of all computer operations
* Generates regular electronic pulses or ticks that set the operating pace of components of system unit

* Each tick is a clock cycle
* Pace of system clock is clock speed.
* Most clock speeds are in the gigahertz (GHz) range ( 1GHz = one billion ticks of system clocks per second) some run at 3.8 GHz
* Processor speed can also be measured in millions of instructaions per second (MIPS)
* If Clock speed = 1 GHz = 1024MHz
	* Typically it could execute 1 instruction per clock tick
	* so it would execute 1024 million instructions per seconds = 1024 MIPS

#### Manufacturers
The leading manufacturers of personal computer chips are intel and AMD

### Heat sinks and pipes
<iframe width="560" height="315" src="https://www.youtube.com/embed/tX2VKEesUiE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

A processor chip generates heat that could cause the chip to burn up, hence it requires additonal cooling:
* heat sink
	* A component with fins that cools the processor
* Liquid cooling
	* uses a continuous flow of fluids to transfer heat away using oil or water
	* mainly used for servers

#### Heat pipes in notebook computers
* A laptop's CPU and GPU heatsinks and copper pipes transferring heat to an exhaust fan expelling hot air
* The heat is expelled from a laptop by an exhaust fan
![](https://lh3.googleusercontent.com/gKC1guma84b4cCKjaHlk9-C91X7Q7xTtlOoF0VBrmId7UFp77h9CckuliUiOFT9EPlBSQzhrxAhU=w1274-h955-no)


### Parallel processing
* Using multiple processors simultaneously  to execute a program faster
* Require special software to divide problem and bring results together
![](https://assets-global.website-files.com/5debb9b4f88fbc3f702d579e/5e8e265f5b27697d5ce9bf87_parallel-computing-diagram.png)

## Data representation
* Analog signals are continuous and vary in strength and quality
	* if signal is weak, picture is weak, lots of static
* Digital are in one of the two states: on or off
	* As long as TV is receiving a signal, picture is perfect

Most computers are digital 
* The binary system uses 2 unique digits (0 and 1)
	* bits and bytes
* Other numbers systems:
	* Hexadecimal
		* The **hexadecimal** numeral system, often shortened to "hex", is a numeral system made up of 16 symbols (base 16).
		* ![](https://miro.medium.com/max/604/1*PkHLh296lpvyEyJ2KPxdSw.png)
	* Octal
		* The **octal** numeral system, or oct for short, is the base-8 number system, and uses the digits 0 to 7
	* decimal

### Byte
Eight bits of 0's and 1's grouped together as a unit
* All the number systems use the positional notation.
* The position determins the weight of the number
Conversion template for converting binary numbers to decimal place

![](https://images.slideplayer.com/25/7731687/slides/slide_6.jpg)

* A byte provide enough different combinations of 0s and 1s to represent 256 individual charaters
* Form a coding system
* eight bit coding system ![](https://www.tpub.com/neets/book22/0068.GIF)

### Coding system
Coding systems make it possible for humans to interact with computers that process only with bits
* Need to input data
	* text
	* image
	* audio
	* video
Coding standards make it possible for computer components to communicate with each other succesfully
* They need to talk using the same language (coding system)

**3 popular coding systems**
1. ASCII
	* American standard code for information interchange
2. EBCDIC
	* Extended Binary Coded Decimal Interchange code
3. Unicode-coding
	* Scheme capable of representing all world's language
		* 16bits per character
		* 65536 symbols
	* ![](https://i.stack.imgur.com/6C0C6.png)
		

## Memory 

Memory consist of electronic components that store:
* instructions waiting to be executed by processor
* data need by those instructions
* the result of processing the data (information)

Stores 3 basic categories of items:
1. The operating system and other system software
2. Application programs
3. Data being processed and the resulting information

Each memory location has an address
* an address is a unique number that identify the location of a byte of memory PC uses a byte addressable memory
* Memory size is measured in:
	* Kilobytes  KB = 2^10^
	* Megabytes  MB = 2^20^
	* Gigabytes  GB = 2^30^
	* Terabytes  TB = 2^40^

The system unit consist of 2 types of memory
* Volatile = temporary
	* loses its contents when power is turned off
	* RAM
* Non- volatile = permanent
	* Does not lose contents when power is removed
	* ROM
	* Flash mem
	* CMOS


### Random access memory
* memory chips that can be read from and written to by processor
* Also called main memory or primary storage
* most RAM is volatile, it is lost when computer's power is turned off
* The more RAM a computer has, the faster it responds

Three basic types of RAM chips
1. Dynamic RAM (DRAM)
	* DRAM needs to be re-energized (refreshed) constantly
2. Static ram (SRAM)
	* faster 
	* reliable
	* More expensive
	* Used for cache 
3. Magnetoresistive ram (MRAM)
	* Newer
	* uses magnetic denser
	* uses less power
	* non-volatile

DRAM variations
* SDRAM = synchronous DRAM
* DDR SDRAM = double data rate SDRAM
* DDR2
* DDR3
* DDR4
* RDRAM = Rambus DRAM

### Memory module
* It is attached to small circuit board called memory module
* Memory slots on motherboard hold memory modules
	* 9 chips: parity check
	* 8 chips: no parity check = newer
![](https://4.imimg.com/data4/CT/HA/MY-8492905/desktop-memory-modules-500x500.jpg)

RAM modules 4 main types:
1. SIMM
	* Single inline memory module
	* pins on the opposite side form a single set of contacts
2. DIMM
	* Dual inline memory module
	* 168 pins on opposite sides of the circuit board form separate connections
3. SODIMM
	* Small outline dual inline memory module
	* A much smaller form of memory 144pin
	* used in notebook computers and apple iMac desktops
4. RIMM
	* RAMbus inline memory module
	* comparable in size and pin configuration to DIMM but uses a special memory bus (RAMbus) to greatly increase speed
	* 184-pin RIMM

#### Refreshing DRAM memory
* This refresh operation is where Dynamic ram gets its name
* Dyanamic ram has to be dynamically refreshed all the time of it forgets what it is holding
* The downside of this is that refreshing takes time and slows down the memory

#### Parity checking
RAM may use parity checking

* Odd parity
	*  The parity bit will be forced to 1 if it is corresponding byte of data contains an even number of 1's 
	* if the byte contains an odd number of 1's the parity bit is forced to 0 or turned off
* Even parity
	* The parity bit is force to 0 if the byte contains an even number of 1's 
	* the parity bit is force to 1 if its corresponding byte of data contains an odd number of 1's

#### Error Control
* High-end servers often have a form of error checkiong known as error correction code (ECC)
* Bits can be corrected after failure, however, if more than one bit is corrupted the entire byte of data is lost
![](https://www.atlantic.net/wp-content/uploads/2016/11/ecc-vs-nonecc.png)

### Static RAM (SRAM)
* Often used for casche memory
* very fast and relaible because these chips do not have to be recharged as often as DRAM hence the term "static"
* More expensive than DRAM

#### Cache
* Cache memory (static ram) helps speed up the processor
* Cache memory stores frequently used data and instructions
	* when the processor needs an instruction or data
	* it searches the memory in the order:
		* L1 cache
		* L2 cache
		* Then L3 if exist
		* Then DRAM
		* ![](https://ecomputertips.com/wp-content/uploads/2020/06/Cache-Memory.jpg)


#### Static RAM L1,L2
Personal computers have 2 and perhaps 3 types of cache memory:
* L1 level 1 cache 8KB to 128KB
* L2 level 2 cache 64KB to 4MB
* L2 advance transfer cache (ATC) on current microprocessors (built on the chip)
	* ATC allows for the L2 cache to reside entirely within the processor core and feature a 256 but wide bus. processors that use ATC perform at a much faster rate

#### Static RAM L3

* L3 level 3 cache is cache separate from the microprocessor chip and is on the motherboard
* L3 cache only exist on computers that use the L2 ATC

L3 may also be on the microprocessor chip as is the case with intel core i7 chip

![](https://hackernoon.com/hn-images/1*nT3RAGnOAWmKmvOBnizNtw.png)

**Intel core i7 quad**
![](https://www.cs.uaf.edu/2009/fall/cs441/proj1/russell/images/df94g6m6_4gxrw53gk_b.png)
* 45nm
* L1 Data 32KB
* L1 Code 32KB
* L2 256 KB per core
* L3 8MB shared with all cores

### Read only memory (ROM)
* Memory chips that store permanent data and instructions
* non-volative memory, it is not lost when computer's power is turned off
* 3 main types
	* ROM
		* Firmware
		* manufactured with permanently written data and instructions
		* mask programmable by chip manufacturer
		* non erasable
	* PROM
		* Programmable ROM
		* blank ROM chip onto which a programmer can write permanently
		* Write once, non erasable
	* EEPROM
		* Electrically erasable programmable ROM
		* Type of PROM containing microcode programmer can erase
		* erasable
		* rewritable

### Flash memory
* Flash memory can be erased electronically and rewritten 
* store data and program on many mobile computers and devices such as smart phones and digital camera
* Flash memory is similar to EEPROM
* it is used to hold the startup instructions 
* allows computer to update its contents easily

Access time is the amount of time it take for the processor to read from memory
* Measure in nanoseconds
	* today's memory has access time from 5 to 70ns
	* nano = 10^-9^
	* pico = 10^-12^
	*  micro = 10^-6^
	*  milli = 10^-3^
Access time can also be the time it takes for the storage device to locate the item on storage medium

Hard disk acccess time = 0.006 = 6 ms
RAM = 60ns
* RAM is more than 100000 times faster than harddisk

## Expansion slots and adapter cards
* enhances the system unit or provides connections to external devices called peripherals
* Also called expansion card

### Expansion slots 
* An openingn or socket on the motherboard that can hold an adapter card
* with plug and play, the computer automatically configures cards and other devices as you install them.
* 

