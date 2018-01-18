<Type Name="IServiceRemotingMessageBodyFactory" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingMessageBodyFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingMessageBodyFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingMessageBodyFactory" />
  <TypeSignature Language="F#" Value="type IServiceRemotingMessageBodyFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79c89-101">Definiert die Schnittstelle, die für das Bereitstellen von Factory zum Erstellen von Remtoing Anforderungstext und Antwort Body-Objekte implementiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="79c89-101">Defines the interface that must be implemented for providing factory for creating remtoing request body and response body objects.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateRequest">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody CreateRequest (string interfaceName, string methodName, int numberOfParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody CreateRequest(string interfaceName, string methodName, int32 numberOfParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory.CreateRequest(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRequest (interfaceName As String, methodName As String, numberOfParameters As Integer) As IServiceRemotingRequestMessageBody" />
      <MemberSignature Language="F#" Value="abstract member CreateRequest : string * string * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" Usage="iServiceRemotingMessageBodyFactory.CreateRequest (interfaceName, methodName, numberOfParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceName" Type="System.String" />
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="numberOfParameters" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="interfaceName"> <span data-ttu-id="79c89-102">Dies ist FullName für die Dienstschnittstelle, die für die Anforderung Text erstellt wird</span><span class="sxs-lookup"><span data-stu-id="79c89-102">This is FullName for the service interface for which request body is being constructed</span></span></param>
        <param name="methodName"><span data-ttu-id="79c89-103">Methodenname für die Dienstschnittstelle, die für der Anforderung an gesendet werden</span><span class="sxs-lookup"><span data-stu-id="79c89-103">MethodName for the service interface for which request will be sent to</span></span></param>
        <param name="numberOfParameters"><span data-ttu-id="79c89-104">Anzahl von Parametern in der Methode</span><span class="sxs-lookup"><span data-stu-id="79c89-104">Number of Parameters in that Method</span></span></param>
        <summary>
            <span data-ttu-id="79c89-105">Erstellt einen Anforderungstext Remoting</span><span class="sxs-lookup"><span data-stu-id="79c89-105">Creates a Remoting Request Body</span></span>
            </summary>
        <returns><span data-ttu-id="79c89-106">IServiceRemotingRequestMessageBody</span><span class="sxs-lookup"><span data-stu-id="79c89-106">IServiceRemotingRequestMessageBody</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponse">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody CreateResponse (string interfaceName, string methodName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody CreateResponse(string interfaceName, string methodName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory.CreateResponse(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateResponse (interfaceName As String, methodName As String) As IServiceRemotingResponseMessageBody" />
      <MemberSignature Language="F#" Value="abstract member CreateResponse : string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody" Usage="iServiceRemotingMessageBodyFactory.CreateResponse (interfaceName, methodName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceName" Type="System.String" />
        <Parameter Name="methodName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="interfaceName"> <span data-ttu-id="79c89-107">Dies ist FullName für die Dienstschnittstelle, die für die Anforderung Text erstellt wird</span><span class="sxs-lookup"><span data-stu-id="79c89-107">This is FullName for the service interface for which request body is being constructed</span></span></param>
        <param name="methodName"><span data-ttu-id="79c89-108">Methodenname für die Dienstschnittstelle, die für der Anforderung an gesendet werden</span><span class="sxs-lookup"><span data-stu-id="79c89-108">MethodName for the service interface for which request will be sent to</span></span></param>
        <summary />
        <returns><span data-ttu-id="79c89-109">IServiceRemotingResponseMessageBody</span><span class="sxs-lookup"><span data-stu-id="79c89-109">IServiceRemotingResponseMessageBody</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>