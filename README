

Initial kernel
==============
gpudev1@ip-10-16-9-218:~/exercises/openacc/001-laplace2D-kernels$ ./laplace2d_acc 
Jacobi relaxation Calculation: 4096 x 4096 mesh
    0, 0.250000
  100, 0.002397
  200, 0.001204
  300, 0.000804
  400, 0.000603
  500, 0.000483
  600, 0.000403
  700, 0.000345
  800, 0.000302
  900, 0.000269
 total: 135.719596 s

Accelerator Kernel Timing data
/home/gpudev1/exercises/openacc/001-laplace2D-kernels/laplace2d.c
  main  NVIDIA  devicenum=0
    time(us): 97,692,259
    56: compute region reached 1000 times
        56: data copyin reached 1000 times
             device time(us): total=22,323,291 max=22,363 min=22,311 avg=22,323
        60: kernel launched 1000 times
            grid: [32x4094]  block: [128]
             device time(us): total=6,743,477 max=6,761 min=6,666 avg=6,743
            elapsed time(us): total=6,753,957 max=6,788 min=6,676 avg=6,753
        60: reduction kernel launched 1000 times
            grid: [1]  block: [256]
             device time(us): total=270,547 max=280 min=268 avg=270
            elapsed time(us): total=281,457 max=319 min=278 avg=281
        69: data copyout reached 1000 times
             device time(us): total=21,691,861 max=21,716 min=21,685 avg=21,691
    69: compute region reached 1000 times
        69: data copyin reached 1000 times
             device time(us): total=22,364,825 max=22,441 min=22,357 avg=22,364
        73: kernel launched 1000 times
            grid: [32x4094]  block: [128]
             device time(us): total=3,564,053 max=3,578 min=3,559 avg=3,564
            elapsed time(us): total=3,580,699 max=3,603 min=3,574 avg=3,580
        79: data copyout reached 1000 times
             device time(us): total=20,734,205 max=20,768 min=20,718 avg=20,734


