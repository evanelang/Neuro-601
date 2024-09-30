# Neuro-601

## Project Definition
A simulated neuromorphic processor on low cost consumer grade FPGA hardware for studying neuromorphic algorithms.

## Project Mission
For neuromorphic researchers, who want to study how to implement and research new neuromorphic algorithms.  The NeuroFPGA is a neuromorphic piece of hardware that allows a lower barrier for entry than using an enterprise hardware unlike Intel’s Loihi, IBM TrueNorth and spikeNNar. Our product is implemented on a standard FPGA which is cheaper and more easily obtainable.

## User Stories
User Story #1: neuromorphic computing researcher

The Card:
  
  As a machine learning researcher, I want to utilize neuromorphic computing architectures for processing data, so that I can improve energy efficiency and performance.
  
The Conversation:
  
  The development team discusses details with the machine learning researcher like:
  
    1.) What kind of data will be processed?
    
    2.) How much data does the researcher want to process at once?
    
    3.) How much energy efficiency improvement is expected?

The Confirmation:
  
  The user story is considered complete when:
  
    1.) The product demonstrates a reduction in energy consumption.
    
    2.) The product can process a lot of data efficiently.
    
    3.) The product can process a wide variety of different types of data.
    


User Story #2: Bio-Computer Interfacing researcher

The Card:
  
  As a neuroprosthetics researcher, I want to test neuromorphic software in a safe environment before deploying it to any live situation so that invasive patient and animal testing can be avoided until safe and necessary and development can move at a faster rate.
  
The Conversation:
  
  The development team discusses details with the machine learning researcher like:
  
    1.) What level of computational power is necessary to accurately mimic the final production hardware?
    
    2.) How will signals from the brain (e.g., EEG or direct neural recordings) be translated into prosthetic control signals?
    
    3.) What are the latency and signal processing requirements for smooth and natural movement control?

    4.) How will the system adapt to individual patients and their unique neural patterns?

    3.) What IO to the processor is necessary to properly convert and utilize the signals researchers' expect to test with?

The Confirmation:
  
  The user story is considered complete when:
  
    1.)	The FPGA based simulation has enough computational power to accurately test software meant for neuroprosthetics.

    2.)	The prosthetic control test system achieves a response time of less than 50 milliseconds from neural signal input to motor action.

    3.)	The bio-computer interface can fully interact with the FPGA simulation.

    4.)	The test FPGA system adapts to test user neural signals over time.

    5.)	A full test suite of complex neural inputs can properly be received, attempted, and reported on to the user.

  
## Citations
[1] Rathi, N., Chakraborty, I., Kosta, A., Sengupta, A., Ankit, A., Panda, P., Roy, K., Nitin RathiSchool of Electrical and Computer Engineering, P. U., Indranil ChakrabortySchool of Electrical and Computer Engineering, P. U., Adarsh KostaSchool of Electrical and Computer Engineering, P. U., Abhronil SenguptaSchool of Electrical Engineering and Computer Science, P. S. U., Aayush AnkitSchool of Electrical and Computer Engineering, P. U., Priyadarshini PandaElectrical Engineering, Y. U., & Kaushik RoySchool of Electrical and Computer Engineering, P. U. (2023, March 2). Exploring neuromorphic computing based on spiking neural networks: Algorithms to hardware. ACM Computing Surveys. https://dl.acm.org/doi/full/10.1145/3571155#sec-1 
[2] L. O. Chua, “Memristor—The missing circuit element,” IEEE Trans. Circuit Theory, vol. CT-18, no. 5, pp. 507–519, Sep. 1971.
[3] D. B. Strukov, G. S. Snider, D. R. Stewart, and R. S. Williams, “The missing memristor found,” Nature, vol. 453, no. 7191, pp. 80–83, May 2008.
[4] J. Borghetti, G. S. Snider, P. J. Kuekes, J. J. Yang, D. R. Stewart, and R. S. Williams. Memristive switches enable stateful logic operations via material implication. Nature, 464(7290):873–876, 2010.
[5] S. Chakraborti, P. V. Chowdhary, K. Datta, and I. Sengupta. BDD based synthesis of Boolean functions using memristors. In 9th International Design and Test Symposium (IDT), pages 136–141, December 2014.
[6] S. Kvatinsky, G. Satat, N. Wald, E. G. Friedman, A. Kolodny, and U. C. Weiser. Memristor-based material implication (IMPLY) logic: Design principles and methodologies. IEEE Transactions on VLSI Systems, 22(10):2054–2066, October 2014.
[7] S. Kvatinsky et al., “MAGIC—Memristor-aided logic,” IEEE Trans. Circuits Syst. II, Exp. Briefs, vol. 61, no. 11, pp. 895–899, Nov. 2014
[8] R. Gharpinde, P. L. Thangkhiew, K. Datta, and I. Sengupta, “A scalable in-memory logic synthesis approach using memristor crossbar,” IEEE Trans. Very Large Scale Integr. (VLSI) Syst., to be published, doi: 10.1109/TVLSI.2017.2763171.
[9] N. Talati, S. Gupta, P. Mane, and S. Kvatinsky, “Logic design within memristive memories using Memristor-Aided loGIC (MAGIC),” IEEE Trans. Nanotechnol., vol. 15, no. 4, pp. 635–650, Jul. 2016.
[10] Li, H., Lee, M. H., et al. (2018). CMOS-compatible fabrication of memristive devices for non-volatile memory and computing applications. Materials Research Express, 5(12), 125026.
[11] P. L. Thangkhiew, R. Gharpinde and K. Datta, "Efficient Mapping of Boolean Functions to Memristor Crossbar Using MAGIC NOR Gates," in IEEE Transactions on Circuits and Systems I: Regular Papers, vol. 65, no. 8, pp. 2466-2476, Aug. 2018, doi: 10.1109/TCSI.2018.2792474.

