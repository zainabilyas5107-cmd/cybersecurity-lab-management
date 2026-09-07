# cybersecurity-lab-management
#include <stdio.h>

int main(){
	
	char LabName[50];
	int NoComputers, NoNetworkDevices, NoSecurityTools, CostPComputer, CostNetworkDevice, AnnSecCost, CompCost, NetwCost, TlabInvest;
	
	printf("Lab Name: ");
	scanf("%s", &LabName);
	
	printf("\nNumber of Computers: ");
	scanf("%d", &NoComputers);
	
	printf("Number of Network Devices: ");
	scanf("%d", &NoNetworkDevices);
	
	printf("Number of Security Tools: ");
	scanf("%d", &NoSecurityTools);
	
	printf("Cost per Computer: ");
	scanf("%d", &CostPComputer);
	
	printf("Cost per Network Device: ");
	scanf("%d", &CostNetworkDevice);
	
	printf("Annual Security Software Cost: ");
	scanf("%d", &AnnSecCost);
	
	CompCost = NoComputers * CostPComputer;
	
	NetwCost = NoNetworkDevices * CostNetworkDevice;
	
	TlabInvest = CompCost + NetwCost + AnnSecCost;
	
	printf("Computer Cost: %d \n", CompCost);
	
	printf("Network Device Cost: %d \n", NetwCost);
	
	printf("Total Lab Investment: %d \n", TlabInvest);
	
	
	
	
	
}
