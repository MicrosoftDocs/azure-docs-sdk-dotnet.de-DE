<Type Name="IServiceRemotingMessageHandler" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingMessageHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingMessageHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingMessageHandler" />
  <TypeSignature Language="F#" Value="type IServiceRemotingMessageHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Schnittstelle, die von der ServiceRemotingListener zum Empfangen von Nachrichten vom Datentransport Remoting implementiert werden muss.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HandleOneWay">
      <MemberSignature Language="C#" Value="public void HandleOneWay (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void HandleOneWay(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler.HandleOneWay(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub HandleOneWay (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte())" />
      <MemberSignature Language="F#" Value="abstract member HandleOneWay : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; unit" Usage="iServiceRemotingMessageHandler.HandleOneWay (requestContext, messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="requestContext">Enthält zusätzliche Informationen über die Anforderung.</param>
        <param name="messageHeaders">Die Anforderungsheader für die Nachricht.</param>
        <param name="requestBody">Der Anforderungstext für die Nachricht.</param>
        <summary>
            Eine unidirektionale Nachricht vom Client verarbeitet.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function RequestResponseAsync (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBody As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iServiceRemotingMessageHandler.RequestResponseAsync (requestContext, messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBody" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="requestContext">Enthält zusätzliche Informationen über die Anforderung.</param>
        <param name="messageHeaders">Die Anforderungsheader für die Nachricht.</param>
        <param name="requestBody">Der Anforderungstext für die Nachricht.</param>
        <summary>
            Verarbeitet eine Nachricht vom Client, der eine Antwort vom Dienst erforderlich sind.
            </summary>
        <returns>der Antworttext.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>