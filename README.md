###Project Overview
This project is based on Python to solve the readers-writers problem

###Core Features
1.Implemented thread synchronization
2.When no writer is active, multiple readers are allowed to access the shared resource simultaneously
3.While a writer is executing, no readers or other writers are permitted to access the shared resource

###File Structure
1.readers_writers.py(main program file)
2.README.md(this file)

###Core method
1.start_read(self, reader_id: int)
2.end_read(self, reader_id: int)
3.start_write(self, writer_id: int)
4.end_write(self, writer_id: int)

###Output result
Writer 1 is WRITING
Writer 2 wants to write
Writer 2 is waiting to write
Writer 1 stops writing
Writer 1 finished writing
Writer 2 starts writing
Writer 2 is WRITING
Writer 2 stops writing
Writer 2 finished writing
Simulation completed successfully!
