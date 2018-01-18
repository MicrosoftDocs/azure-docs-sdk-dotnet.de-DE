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
    <summary><span data-ttu-id="2ec08-101">Die nachrichtensicherheit für eine unidirektionale Verbindung über das Azure Service Bus-Relay.</span><span class="sxs-lookup"><span data-stu-id="2ec08-101">The message security on a one-way connection over the Azure Service Bus relay.</span></span></summary>
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
        <summary><span data-ttu-id="2ec08-102">Ruft ab oder legt die algorithmussammlung zum Sichern von Nachrichten auf der SOAP-Ebene verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="2ec08-102">Gets or sets the algorithm suite to be used for securing messages at the SOAP level.</span></span></summary>
        <value><span data-ttu-id="2ec08-103">Gibt eine <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> , welches algorithmuspaket enthält.</span><span class="sxs-lookup"><span data-stu-id="2ec08-103">Returns an <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> containing the algorithm suite.</span></span> <span data-ttu-id="2ec08-104">Der Standardwert ist Basic256, die 256-Bit-Advanced Encryption Standard (AES) als symmetrischen Verschlüsselungsalgorithmus angibt.</span><span class="sxs-lookup"><span data-stu-id="2ec08-104">The default is Basic256, which specifies 256-bit Advanced Encryption Standard (AES) as the symmetric encryption algorithm.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="2ec08-105">Der Wert, der die <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="2ec08-105">The value of the <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> is null.</span></span></exception>
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
        <summary><span data-ttu-id="2ec08-106">Ruft ab oder legt den Typ der Clientanmeldeinformationen an, die der Client verwendet, um sich an den Dienst auf der SOAP-Ebene zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="2ec08-106">Gets or sets the type of client credential the client uses to authenticate itself to the service at the SOAP level.</span></span></summary>
        <value><span data-ttu-id="2ec08-107">Gibt eine <see cref="T:System.ServiceModel.MessageCredentialType" /> , die den Typ der Anmeldeinformationen enthält.</span><span class="sxs-lookup"><span data-stu-id="2ec08-107">Returns a <see cref="T:System.ServiceModel.MessageCredentialType" /> that contains the credential type.</span></span> <span data-ttu-id="2ec08-108">Der Standardwert ist Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="2ec08-108">The default is Certificate.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="2ec08-109">Der Wert von <see cref="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" /> ist kein gültiger <see cref="T:System.ServiceModel.MessageCredentialType" />.</span><span class="sxs-lookup"><span data-stu-id="2ec08-109">The value of <see cref="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" /> is not a valid <see cref="T:System.ServiceModel.MessageCredentialType" />.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>