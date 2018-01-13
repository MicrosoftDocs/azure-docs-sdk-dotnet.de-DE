<Type Name="ServicePlacementPreferPrimaryDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementPreferPrimaryDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementPreferPrimaryDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementPreferPrimaryDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementPreferPrimaryDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServicePlacementPolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="0c676-101">Stellt eine <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> gibt an, dass die primären Replikate der Dienst in einer bestimmten Domäne optimal platziert werden soll.</span><span class="sxs-lookup"><span data-stu-id="0c676-101">Represents a <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> which indicates that the service’s Primary replicas should optimally be placed in a particular domain.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="0c676-102">Diese Einschränkung wird in der Regel mit Fehlerdomänen in Szenarien verwendet, auf dem Service Fabric-Cluster geografisch verteilt wird, um anzugeben, dass das primäre Replikat für einen Dienst in einer bestimmten Fehlerdomäne, welche in Szenarien mit geografisch verteilten befinden soll in der Regel mit regionalen oder Datacenter-Grenzen ausgerichtet.</span><span class="sxs-lookup"><span data-stu-id="0c676-102">This constraint is usually used with fault domains in scenarios where the Service Fabric cluster is geographically distributed in order to indicate that a service’s primary replica should be located in a particular fault domain, which in geo-distributed scenarios usually aligns with regional or datacenter boundaries.</span></span> <span data-ttu-id="0c676-103">Beachten Sie, da dies eine Optimierung ist es möglich ist, dass das primäre Replikat nicht in dieser Domäne aufgrund von Fehlern, Kapazitätsgrenzen oder andere Einschränkungen befinden annehmen kann.</span><span class="sxs-lookup"><span data-stu-id="0c676-103">Note that since this is an optimization it is possible that the Primary replica may not end up located in this domain due to failures, capacity limits, or other constraints.</span></span></para>
    </remarks>
    <example>
      <code>
            <span data-ttu-id="0c676-104">Erstellen Sie den Dienst Platzierung Richtlinie ServicePlacementPreferPrimaryDomainPolicyDescription PlacementPolicy = neue ServicePlacementPreferPrimaryDomainPolicyDescription(); placementPolicy.DomainName = @"fd:\Datacenter1";</span><span class="sxs-lookup"><span data-stu-id="0c676-104">//create the service placement policy ServicePlacementPreferPrimaryDomainPolicyDescription placementPolicy = new ServicePlacementPreferPrimaryDomainPolicyDescription(); placementPolicy.DomainName = @"fd:\Datacenter1";</span></span>
            
            <span data-ttu-id="0c676-105">Die Stateful Service Beschreibung StatefulServiceDescription Ssd hinzufügen = neue StatefulServiceDescription(); SSD. PlacementPolicies.Add(placementPolicy);</span><span class="sxs-lookup"><span data-stu-id="0c676-105">//add it to the Stateful Service Description StatefulServiceDescription ssd = new StatefulServiceDescription(); ssd.PlacementPolicies.Add(placementPolicy);</span></span></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementPreferPrimaryDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="0c676-106">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="0c676-106">initializing a new instance of the <see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.DomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0c676-107">Ruft ab, oder legt ihn fest den Zeichenfolgennamen der Domäne, in der das primäre Replikat vorzugsweise gefunden werden soll.</span><span class="sxs-lookup"><span data-stu-id="0c676-107">Gets or sets the string name of the domain in which the Primary replica should be preferentially located.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0c676-108">Der Zeichenfolgenname der Domäne, in der das primäre Replikat vorzugsweise gefunden werden soll.</span><span class="sxs-lookup"><span data-stu-id="0c676-108">The string name of the domain in which the Primary replica should be preferentially located.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementPreferPrimaryDomainPolicyDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para> 
            <span data-ttu-id="0c676-109">Eine Zeichenfolgendarstellung der PreferPrimaryDomain Platzierung Dienstrichtlinie in Form 'PreferPrimaryDomain, DomainName' zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="0c676-109">Return a string representation of the PreferPrimaryDomain Service Placement Policy in the form 'PreferPrimaryDomain, DomainName'</span></span> 
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="0c676-110">Eine Zeichenfolge, die das Objekt darstellt.</span><span class="sxs-lookup"><span data-stu-id="0c676-110">A string representing the object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>