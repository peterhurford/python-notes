Computer has many bytes of memory, each given a sequential memory address with O(1) lookup

Python identifiers keep track of the memory address of the object of reference

A basic array group of items stored in contiguous memory locations. Every element must have the same number of bytes. This allows one to access element m in O(1) by simply accessing the memory location associated with the initial location for element 0 + the size of each object * m. 

Python can expand the basic array to a list of heterogeneous types and sizes by storing a basic array of references to those objects

Python array class from array module stores items in a basic array and can only support homogeneous types. It is initialized with a type parameter. array('i', [2, 3, 5, 7])

Table 5.1 on p191

Basic arrays have to be allocated in advance and therefore cannot change size. This is fine for immutable tuples and str that are thus defined once.

Dynamic arrays allow resizing by storing a basic array and a length reference. If length is to be exceeded, a new and larger basic array will be allocated and all the objects copied over. The list typically is implemented to double in size each time.

sys.getsizeof(x) tells the size of x in memory
