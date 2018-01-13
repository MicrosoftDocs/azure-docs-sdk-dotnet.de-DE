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
            Definiert die Schnittstelle, die für das Bereitstellen von Factory zum Erstellen von Remtoing Anforderungstext und Antwort Body-Objekte implementiert werden muss.
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
        <param name="interfaceName"> Dies ist FullName für die Dienstschnittstelle, die für die Anforderung Text erstellt wird</param>
        <param name="methodName">Methodenname für die Dienstschnittstelle, die für der Anforderung an gesendet werden</param>
        <param name="numberOfParameters">Anzahl von Parametern in der Methode</param>
        <summary>
            Erstellt einen Anforderungstext Remoting
            </summary>
        <returns>IServiceRemotingRequestMessageBody</returns>
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
        <param name="interfaceName"> Dies ist FullName für die Dienstschnittstelle, die für die Anforderung Text erstellt wird</param>
        <param name="methodName">Methodenname für die Dienstschnittstelle, die für der Anforderung an gesendet werden</param>
        <summary />
        <returns>IServiceRemotingResponseMessageBody</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>