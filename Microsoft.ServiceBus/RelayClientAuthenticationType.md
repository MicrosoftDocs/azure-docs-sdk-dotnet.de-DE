<Type Name="RelayClientAuthenticationType" FullName="Microsoft.ServiceBus.RelayClientAuthenticationType">
  <TypeSignature Language="C#" Value="public enum RelayClientAuthenticationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RelayClientAuthenticationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum RelayClientAuthenticationType" />
  <TypeSignature Language="F#" Value="type RelayClientAuthenticationType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RelayClientAuthenticationType", Namespace="http://schemas.microsoft.com/netservices/2009/05/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Beschreibt, ob Clients eines Diensts erforderlich sind, um ein Sicherheitstoken von Azure Access Control ausgestellt an den Azure-Servicebus beim Senden von Nachrichten zu präsentieren.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayClientAuthenticationType None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="Microsoft.ServiceBus.RelayClientAuthenticationType.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Wenn von einem Listener angegeben wird, benötigt der Client nicht kein Sicherheitstoken bereitstellen. Dies stellt einen Opt-Out-Mechanismus, mit dem Listener den Azure Access Control-Schutz für den Endpunkt aufheben können.</summary>
      </Docs>
    </Member>
    <Member MemberName="RelayAccessToken">
      <MemberSignature Language="C#" Value="RelayAccessToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayAccessToken = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />
      <MemberSignature Language="VB.NET" Value="RelayAccessToken" />
      <MemberSignature Language="F#" Value="RelayAccessToken = 0" Usage="Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>Wenn von einem Listener angegeben wird, muss der Client kein Sicherheitstoken bereitstellen. </summary>
      </Docs>
    </Member>
  </Members>
</Type>