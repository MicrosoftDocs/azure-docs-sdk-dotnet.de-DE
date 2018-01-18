<Type Name="NamespaceManagerSettings" FullName="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManagerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManagerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManagerSettings" />
  <TypeSignature Language="F#" Value="type NamespaceManagerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d5dac-101">Enthält die Einstellungen für den NamespaceManager.</span><span class="sxs-lookup"><span data-stu-id="d5dac-101">Contains the settings for the namespace manager.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManagerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d5dac-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d5dac-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d5dac-103">Abrufen oder Festlegen des Zeitlimits Vorgang für alle Namespace dienstverwaltungsvorgänge, wie z. B. GetQueue CreateQueue und So weiter.</span><span class="sxs-lookup"><span data-stu-id="d5dac-103">Gets or sets the operation timeout period for all service namespace management operations, such as GetQueue, CreateQueue, and so on.</span></span></summary>
        <value><span data-ttu-id="d5dac-104">Ein <see cref="T:System.TimeSpan" /> -Objekt, das Timeout darstellt.</span><span class="sxs-lookup"><span data-stu-id="d5dac-104">A <see cref="T:System.TimeSpan" /> object that represents the timeout period.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="d5dac-105">löst aus, wenn ein NULL-Wert festgelegt ist – z. B. ein NULL-Werte zulassen TimeSpan-Objekt.</span><span class="sxs-lookup"><span data-stu-id="d5dac-105">throws if a null is set - e.g. a nullable TimeSpan.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="d5dac-106">löst aus, wenn eine 0 (null) oder Negative TimeSpan festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="d5dac-106">throws when a zero or negative TimeSpan is set.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.NotificationHubs.RetryPolicy with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d5dac-107">Ruft ab oder legt die basisimplementierung für die wiederholungsversuchmechanismus für unzuverlässige Aktionen und vorübergehende Bedingungen, die dem Namespacemanager zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="d5dac-107">Gets or sets the base implementation of the retry mechanism for unreliable actions and transient conditions associated with the namespace manager.</span></span></summary>
        <value><span data-ttu-id="d5dac-108">Die basisimplementierung der wiederholungsversuchmechanismus für unzuverlässige Aktionen und vorübergehende Bedingungen, die dem Namespacemanager zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="d5dac-108">The base implementation of the retry mechanism for unreliable actions and transient conditions associated with the namespace manager.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.NotificationHubs.TokenProvider with get, set" Usage="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d5dac-109">Ruft ab oder legt der Anbieter von Sicherheitstoken.</span><span class="sxs-lookup"><span data-stu-id="d5dac-109">Gets or sets the security token provider.</span></span></summary>
        <value><span data-ttu-id="d5dac-110">Der Sicherheitstokenanbieter.</span><span class="sxs-lookup"><span data-stu-id="d5dac-110">The security token provider.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>