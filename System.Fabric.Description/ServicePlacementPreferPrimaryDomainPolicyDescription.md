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
      <para>Stellt eine <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> gibt an, dass die primären Replikate der Dienst in einer bestimmten Domäne optimal platziert werden soll.</para>
    </summary>
    <remarks>
      <para>Diese Einschränkung wird in der Regel mit Fehlerdomänen in Szenarien verwendet, auf dem Service Fabric-Cluster geografisch verteilt wird, um anzugeben, dass das primäre Replikat für einen Dienst in einer bestimmten Fehlerdomäne, welche in Szenarien mit geografisch verteilten befinden soll in der Regel mit regionalen oder Datacenter-Grenzen ausgerichtet. Beachten Sie, da dies eine Optimierung ist es möglich ist, dass das primäre Replikat nicht in dieser Domäne aufgrund von Fehlern, Kapazitätsgrenzen oder andere Einschränkungen befinden annehmen kann.</para>
    </remarks>
    <example>
      <code>
            Erstellen Sie den Dienst Platzierung Richtlinie ServicePlacementPreferPrimaryDomainPolicyDescription PlacementPolicy = neue ServicePlacementPreferPrimaryDomainPolicyDescription(); placementPolicy.DomainName = @"fd:\Datacenter1";
            
            Die Stateful Service Beschreibung StatefulServiceDescription Ssd hinzufügen = neue StatefulServiceDescription(); SSD. PlacementPolicies.Add(placementPolicy);</code>
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
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" /> Klasse.</para>
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
          <para>Ruft ab, oder legt ihn fest den Zeichenfolgennamen der Domäne, in der das primäre Replikat vorzugsweise gefunden werden soll.</para>
        </summary>
        <value>
          <para>Der Zeichenfolgenname der Domäne, in der das primäre Replikat vorzugsweise gefunden werden soll.</para>
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
            Eine Zeichenfolgendarstellung der PreferPrimaryDomain Platzierung Dienstrichtlinie in Form 'PreferPrimaryDomain, DomainName' zurückgeben. 
            </para>
        </summary>
        <returns>
          <para>Eine Zeichenfolge, die das Objekt darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>