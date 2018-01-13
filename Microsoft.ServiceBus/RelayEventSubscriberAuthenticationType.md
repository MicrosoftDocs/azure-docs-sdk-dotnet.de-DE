<Type Name="RelayEventSubscriberAuthenticationType" FullName="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType">
  <TypeSignature Language="C#" Value="public enum RelayEventSubscriberAuthenticationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RelayEventSubscriberAuthenticationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum RelayEventSubscriberAuthenticationType" />
  <TypeSignature Language="F#" Value="type RelayEventSubscriberAuthenticationType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Beschreibt, ob Abonnenten ein <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> erforderlich, um beim Senden von Nachrichten an den Azure Service Bus-Dienst von Azure-Zugriffssteuerungsdienst ausgestelltes Sicherheitstoken vorhanden sind.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Wenn von einem Abonnenten NetEventRelay angegeben, der Client nicht müssen relayzugriffstoken bereitstellen. Dies stellt einen Opt-Out-Mechanismus, mit dem Listener den Azure Access Control-Schutz für den Endpunkt aufheben und ihre eigene Zugriffssteuerung ausführen können.</summary>
      </Docs>
    </Member>
    <Member MemberName="RelayAccessToken">
      <MemberSignature Language="C#" Value="RelayAccessToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType RelayAccessToken = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.RelayAccessToken" />
      <MemberSignature Language="VB.NET" Value="RelayAccessToken" />
      <MemberSignature Language="F#" Value="RelayAccessToken = 0" Usage="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.RelayAccessToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>Wenn von einem Listener NetEventRelay angegeben wird, ist der Client erforderlich, um ein relayzugriffstoken bereitstellen. </summary>
      </Docs>
    </Member>
  </Members>
</Type>