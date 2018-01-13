<Type Name="MessageSecurityOverRelayOneway" FullName="Microsoft.ServiceBus.MessageSecurityOverRelayOneway">
  <TypeSignature Language="C#" Value="public sealed class MessageSecurityOverRelayOneway" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageSecurityOverRelayOneway extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.MessageSecurityOverRelayOneway" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageSecurityOverRelayOneway" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayOneway = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Die nachrichtensicherheit für eine unidirektionale Verbindung über das Azure Service Bus-Relay.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayOneway.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die algorithmussammlung zum Sichern von Nachrichten auf der SOAP-Ebene verwendet werden soll.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> , welches algorithmuspaket enthält. Der Standardwert ist Basic256, die 256-Bit-Advanced Encryption Standard (AES) als symmetrischen Verschlüsselungsalgorithmus angibt.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Der Wert, der die <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Typ der Clientanmeldeinformationen an, die der Client verwendet, um sich an den Dienst auf der SOAP-Ebene zu authentifizieren.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.MessageCredentialType" /> , die den Typ der Anmeldeinformationen enthält. Der Standardwert ist Zertifikat.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Der Wert von <see cref="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" /> ist kein gültiger <see cref="T:System.ServiceModel.MessageCredentialType" />.</exception>
      </Docs>
    </Member>
  </Members>
</Type>