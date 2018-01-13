<Type Name="IServiceRemotingResponseMessageBodySerializer" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingResponseMessageBodySerializer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingResponseMessageBodySerializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingResponseMessageBodySerializer" />
  <TypeSignature Language="F#" Value="type IServiceRemotingResponseMessageBodySerializer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert eine Schnittstelle, die implementiert werden muss, um ein Serialisierungsprogramm für Remoting Antworttext bereitstellen
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody Deserialize (Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody Deserialize(class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer.Deserialize(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Public Function Deserialize (messageBody As IncomingMessageBody) As IServiceRemotingResponseMessageBody" />
      <MemberSignature Language="F#" Value="abstract member Deserialize : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody" Usage="iServiceRemotingResponseMessageBodySerializer.Deserialize messageBody" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IncomingMessageBody" />
      </Parameters>
      <Docs>
        <param name="messageBody">serialisierte Meldung</param>
        <summary>
            Deserialisieren Sie die eingehende Nachricht eine Remoting ResponseMessageBody vor dem Senden an den Client-Api
            </summary>
        <returns>IServiceRemotingResponseMessageBody</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody Serialize (Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody serviceRemotingRequestMessageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody Serialize(class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody serviceRemotingRequestMessageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer.Serialize(Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Public Function Serialize (serviceRemotingRequestMessageBody As IServiceRemotingResponseMessageBody) As OutgoingMessageBody" />
      <MemberSignature Language="F#" Value="abstract member Serialize : Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody" Usage="iServiceRemotingResponseMessageBodySerializer.Serialize serviceRemotingRequestMessageBody" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.OutgoingMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceRemotingRequestMessageBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody" />
      </Parameters>
      <Docs>
        <param name="serviceRemotingRequestMessageBody"></param>
        <summary>
            Serialisieren der Antworttext Remoting vor dem Senden der Nachricht übertragen.
            </summary>
        <returns>OutgoingMessageBody</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>