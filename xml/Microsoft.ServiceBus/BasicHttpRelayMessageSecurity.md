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
    <summary><span data-ttu-id="a0a5d-101">Stellt Eigenschaften zum Konfigurieren von Sicherheit auf Nachrichtenebene Einstellungen für <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-101">Provides properties used to configure message-level security settings for <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span>
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
        <summary><span data-ttu-id="a0a5d-102">Gibt die Algorithmussuite an, die mit <see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" /> verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-102">Specifies the algorithm suite to use with <see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" />.</span></span></summary>
        <value><span data-ttu-id="a0a5d-103">Gibt eine <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />, die 256-Bit-Advanced Encryption Standard (AES) als symmetrischen Verschlüsselungsalgorithmus angibt.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-103">Returns a <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />, which specifies 256-bit Advanced Encryption Standard (AES) as the symmetric encryption algorithm.</span></span> <span data-ttu-id="a0a5d-104">Der Standardwert ist Base256.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-104">The default value is Base256.</span></span> <span data-ttu-id="a0a5d-105">Diese Eigenschaft darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-105">This property cannot be null.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="a0a5d-106">Der Wert des <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-106">The value of <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> is null.</span></span></exception>
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
        <summary><span data-ttu-id="a0a5d-107">Gibt die Art der Anmeldeinformationen an, die der Client authentifiziert.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-107">Specifies the type of credential with which the client authenticates.</span></span></summary>
        <value><span data-ttu-id="a0a5d-108">Gibt eine <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> , enthält ein Mitglied der <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> Enumeration.</span><span class="sxs-lookup"><span data-stu-id="a0a5d-108">Returns a <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> that contains a member of the <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> enumeration.</span></span> <span data-ttu-id="a0a5d-109">Der Standardwert ist UserName...</span><span class="sxs-lookup"><span data-stu-id="a0a5d-109">The default value is UserName..</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>