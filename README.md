# Way to connect the valeiraConnect

pip installation:
pip install valeiraConnect==0.1

code:
import valeiraConnect

mycontent=valeiraConnect.llmConnect(
    azure_endpoint = "<azure-endpoint>, 
    api_key="<api-key>",  
    api_version="<api-version>"
)

output=mycontent.generate("<prompt template in list format>",<model-name>,"<type of output needed e.g-Json,String>")
print(output)
