<Type Name="NamespaceManagerSettings" FullName="Microsoft.ServiceBus.NamespaceManagerSettings">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManagerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManagerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NamespaceManagerSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManagerSettings" />
  <TypeSignature Language="F#" Value="type NamespaceManagerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="0105d-101">Enthält die Einstellungen für den NamespaceManager.</span><span class="sxs-lookup"><span data-stu-id="0105d-101">Contains the settings for the namespace manager.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManagerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManagerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="0105d-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0105d-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0105d-103">Abrufen oder Festlegen des Zeitlimits Vorgang für alle Namespace dienstverwaltungsvorgänge, wie z. B. GetQueue CreateQueue und So weiter.</span><span class="sxs-lookup"><span data-stu-id="0105d-103">Gets or sets the operation timeout period for all service namespace management operations, such as GetQueue, CreateQueue, and so on.</span></span></summary>
        <value><span data-ttu-id="0105d-104">Ein <see cref="T:System.TimeSpan" /> -Objekt, das Timeout darstellt.</span><span class="sxs-lookup"><span data-stu-id="0105d-104">A <see cref="T:System.TimeSpan" /> object that represents the timeout period.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManagerSettings.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.ServiceBus.RetryPolicy with get, set" Usage="Microsoft.ServiceBus.NamespaceManagerSettings.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0105d-105">Ruft ab oder legt die basisimplementierung für die wiederholungsversuchmechanismus für unzuverlässige Aktionen und vorübergehende Bedingungen, die dem Namespacemanager zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0105d-105">Gets or sets the base implementation of the retry mechanism for unreliable actions and transient conditions associated with the namespace manager.</span></span></summary>
        <value><span data-ttu-id="0105d-106">Die basisimplementierung der wiederholungsversuchmechanismus für unzuverlässige Aktionen und vorübergehende Bedingungen, die dem Namespacemanager zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0105d-106">The base implementation of the retry mechanism for unreliable actions and transient conditions associated with the namespace manager.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.ServiceBus.TokenProvider with get, set" Usage="Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0105d-107">Ruft ab oder legt der Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="0105d-107">Gets or sets the security token provider.</span></span></summary>
        <value><span data-ttu-id="0105d-108">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="0105d-108">The security token provider.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>