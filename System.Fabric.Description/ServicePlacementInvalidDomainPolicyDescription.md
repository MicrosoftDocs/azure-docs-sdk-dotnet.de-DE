<Type Name="ServicePlacementInvalidDomainPolicyDescription" FullName="System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class ServicePlacementInvalidDomainPolicyDescription : System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePlacementInvalidDomainPolicyDescription extends System.Fabric.Description.ServicePlacementPolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePlacementInvalidDomainPolicyDescription&#xA;Inherits ServicePlacementPolicyDescription" />
  <TypeSignature Language="F#" Value="type ServicePlacementInvalidDomainPolicyDescription = class&#xA;    inherit ServicePlacementPolicyDescription" />
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
      <para>Stellt eine Richtlinie gibt an, dass auf einen bestimmten Fehler oder upgradedomäne nicht verwendet werden soll für die Platzierung der Instanzen oder Replikate des Diensts, diese Richtlinie angewendet wird.</para>
    </summary>
    <remarks>
      <para>Beispielsweise können in geografisch verteilten Ringe gibt es möglicherweise ein Diensts, der nicht in einer bestimmten Region aufgrund politische oder rechtliche Anforderungen ausgeführt werden muss. In diesem Fall kann diese Domäne als ungültig mit dieser Richtlinie definiert werden. </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePlacementInvalidDomainPolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainName">
      <MemberSignature Language="C#" Value="public string DomainName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.DomainName" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainName As String" />
      <MemberSignature Language="F#" Value="member this.DomainName : string with get, set" Usage="System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.DomainName" />
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
          <para>Ruft ab oder legt den Namen der die Fehlerdomäne als Zeichenfolge, dass es an diesen Dienst in ungültig ist.</para>
        </summary>
        <value>
          <para>Der Name der die Fehlerdomäne als Zeichenfolge, dass es an diesen Dienst in ungültig ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="servicePlacementInvalidDomainPolicyDescription.ToString " />
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
            Eine Zeichenfolgendarstellung der InvalidDomain Platzierung Dienstrichtlinie in Form 'InvalidDomain, DomainName' zurückgeben. 
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