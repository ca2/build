

1.       Create Linux Box with "build" username
1.b.     (Optional) Shutdown
1.b.o.   (Optional) Box Snapshot


2.       wget https://ca2.software/build/linux/prepare_box
2.b.     chmod +x prepare_box
2.c.     ./prepare_box
2.d.     (Optional) Shutdown
2.d.o.   (Optional) Box Snapshot


3.       wget https://ca2.software/build/linux/prepare_simple
3.b.     chmod +x prepare_simple
3.c.     ./prepare_simple
3.d.     (Optional) Shutdown
3.d.o.   (Optional) Box Snapshot

4.a.     cd <build-folder>
4.b.     setup_build
4.c.     make -j <number-of-parallel-tasks>


5.       <build-folder>/output is "Output" folder



