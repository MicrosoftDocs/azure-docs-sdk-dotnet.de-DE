<Type Name="ApplicationHealthState" FullName="System.Fabric.Health.ApplicationHealthState">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type ApplicationHealthState = class&#xA;    inherit EntityHealthState" />
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
      <para><span data-ttu-id="2600f-101">Stellt den Integritätsstatus einer Anwendung, die Anwendungs-ID und der aggregierte Integritätszustand enthält.</span><span class="sxs-lookup"><span data-stu-id="2600f-101">Represents the health state of an application, which contains the application identifier and the aggregated health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthState.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthState.ApplicationName" />
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
          <para><span data-ttu-id="2600f-102">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="2600f-102">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2600f-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="2600f-103">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthState.ToString " />
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
            <span data-ttu-id="2600f-104">Ruft eine zeichenfolgenbeschreibung des Integritätsstatus Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="2600f-104">Gets a string description of the application health state.</span></span>
            </summary>
        <returns><span data-ttu-id="2600f-105">Beschreibung der Anwendung eine Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="2600f-105">String description of the application.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>