在vivado的testbench当中加

initial begin

$dumpfile("wavechech.vcd");

$dumpvars;

end

导出vcd文件后在vscode中查看波形。

