<Type Name="BasicHttpRelayMessageSecurity" FullName="Microsoft.ServiceBus.BasicHttpRelayMessageSecurity">
  <TypeSignature Language="C#" Value="public sealed class BasicHttpRelayMessageSecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BasicHttpRelayMessageSecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BasicHttpRelayMessageSecurity" />
  <TypeSignature Language="F#" Value="type BasicHttpRelayMessageSecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt Eigenschaften zum Konfigurieren von Sicherheit auf Nachrichtenebene Einstellungen für <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt die Algorithmussuite an, die mit <see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" /> verwendet werden soll.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />, die 256-Bit-Advanced Encryption Standard (AES) als symmetrischen Verschlüsselungsalgorithmus angibt. Der Standardwert ist Base256. Diese Eigenschaft darf nicht null sein.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Der Wert des <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.BasicHttpMessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.BasicHttpMessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As BasicHttpMessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.BasicHttpMessageCredentialType with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.BasicHttpMessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt die Art der Anmeldeinformationen an, die der Client authentifiziert.</summary>
        <value>Gibt eine <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> , enthält ein Mitglied der <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> Enumeration. Der Standardwert ist UserName...</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>