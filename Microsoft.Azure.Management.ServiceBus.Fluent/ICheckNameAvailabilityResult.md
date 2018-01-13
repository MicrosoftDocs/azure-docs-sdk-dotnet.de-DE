<Type Name="ICheckNameAvailabilityResult" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public interface ICheckNameAvailabilityResult : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICheckNameAvailabilityResult implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICheckNameAvailabilityResult&#xA;Implements IHasInner(Of CheckNameAvailabilityResultInner)" />
  <TypeSignature Language="F#" Value="type ICheckNameAvailabilityResult = interface&#xA;    interface IHasInner&lt;CheckNameAvailabilityResultInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e3800-101">Das Ergebnis der Überprüfung für die Verfügbarkeit eines Service Bus-Namespace.</span><span class="sxs-lookup"><span data-stu-id="e3800-101">The result of checking for Service Bus namespace name availability.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="e3800-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e3800-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="IsAvailable">
      <MemberSignature Language="C#" Value="public bool IsAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.IsAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAvailable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAvailable : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.IsAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3800-103">Ruft einen booleschen Wert, der angibt, ob der Name für die Verwendung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="e3800-103">Gets a boolean value that indicates whether the name is available for you to use.</span></span> <span data-ttu-id="e3800-104">Bei "true", ist der Name verfügbar.</span><span class="sxs-lookup"><span data-stu-id="e3800-104">If true, the name is available.</span></span> <span data-ttu-id="e3800-105">Wenn "false" wird der Name wurde bereits ausgeführt oder ist ungültig und kann nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e3800-105">If false, the name has already been taken or invalid and cannot be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnavailabilityMessage">
      <MemberSignature Language="C#" Value="public string UnavailabilityMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UnavailabilityMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnavailabilityMessage As String" />
      <MemberSignature Language="F#" Value="member this.UnavailabilityMessage : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3800-106">Ruft eine Fehlermeldung angezeigt, die den Wert für den Grund im Detail erläutert.</span><span class="sxs-lookup"><span data-stu-id="e3800-106">Gets an error message explaining the Reason value in more detail.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnavailabilityReason">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason UnavailabilityReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason UnavailabilityReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnavailabilityReason As UnavailableReason" />
      <MemberSignature Language="F#" Value="member this.UnavailabilityReason : Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3800-107">Ruft die UnavailabilityReason, dass ein Namespacename konnte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e3800-107">Gets the unavailabilityReason that a namespace name could not be used.</span></span> <span data-ttu-id="e3800-108">Der Grund-Element wird nur zurückgegeben, wenn NameAvailable auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="e3800-108">The Reason element is only returned if NameAvailable is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>