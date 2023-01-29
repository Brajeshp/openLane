After installing docker on "Ubuntu 20.04.3 LTS", run following command,
1. git clone https://github.com/efabless/openlane.git --branch rc7
2. cd openlane/
3. export PDK_ROOT=
4. make openlane
5. make pdk
6. make test # This is to test that the flow and the pdk were properly installed

Note:- Step-6, should produce a clean run for the spm. The final layout will be generated at: ./designs/spm/runs/openlane_test/results/magic/spm.gds.
