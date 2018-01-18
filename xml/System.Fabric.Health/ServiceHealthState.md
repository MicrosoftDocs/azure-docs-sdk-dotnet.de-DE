<Type Name="ServiceHealthState" FullName="System.Fabric.Health.ServiceHealthState">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type ServiceHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="94a81-101">Stellt den Integritätsstatus eines Diensts, die die Dienst-ID und der aggregierte Integritätszustand enthält.</span><span class="sxs-lookup"><span data-stu-id="94a81-101">Represents the health state of a service, which contains the service identifier and its aggregated health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthState.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealthState.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="94a81-102">Ruft den Dienstnamen ab.</span><span class="sxs-lookup"><span data-stu-id="94a81-102">Gets the service name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="94a81-103">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="94a81-103">The service name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthState.ToString " />
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
            <span data-ttu-id="94a81-104">Erstellt eine zeichenfolgenbeschreibung des Dienst-Integritätsstatus.</span><span class="sxs-lookup"><span data-stu-id="94a81-104">Creates a string description of the service health state.</span></span>
            </summary>
        <returns><span data-ttu-id="94a81-105">Zeichenfolgenbeschreibung des der <see cref="T:System.Fabric.Health.ServiceHealthState" />.</span><span class="sxs-lookup"><span data-stu-id="94a81-105">String description of the <see cref="T:System.Fabric.Health.ServiceHealthState" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>