<Type Name="ODATAMonitorControl" FullName="Microsoft.Azure.Batch.ODATAMonitorControl">
  <TypeSignature Language="C#" Value="public class ODATAMonitorControl" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ODATAMonitorControl extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ODATAMonitorControl" />
  <TypeSignature Language="VB.NET" Value="Public Class ODATAMonitorControl" />
  <TypeSignature Language="F#" Value="type ODATAMonitorControl = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1d96e-101">Enthält Einstellungen für eine optimale Abruf von Daten über OData-Prädikate verwendet.</span><span class="sxs-lookup"><span data-stu-id="1d96e-101">Contains control settings used for optimal retrieval of state data via OData predicates.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATAMonitorControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATAMonitorControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DelayBetweenDataFetch">
      <MemberSignature Language="C#" Value="public TimeSpan DelayBetweenDataFetch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DelayBetweenDataFetch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATAMonitorControl.DelayBetweenDataFetch" />
      <MemberSignature Language="VB.NET" Value="Public Property DelayBetweenDataFetch As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DelayBetweenDataFetch : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.ODATAMonitorControl.DelayBetweenDataFetch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d96e-102">Die Mindestzeit zwischen Versuche zum Abrufen von Daten für eine überwachte Instanz.</span><span class="sxs-lookup"><span data-stu-id="1d96e-102">The minimum time between attempts to fetch data for a monitored instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ODATAPredicateLimit">
      <MemberSignature Language="C#" Value="public int ODATAPredicateLimit;" />
      <MemberSignature Language="ILAsm" Value=".field public int32 ODATAPredicateLimit" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.ODATAMonitorControl.ODATAPredicateLimit" />
      <MemberSignature Language="VB.NET" Value="Public ODATAPredicateLimit As Integer " />
      <MemberSignature Language="F#" Value="val mutable ODATAPredicateLimit : int" Usage="Microsoft.Azure.Batch.ODATAMonitorControl.ODATAPredicateLimit" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d96e-103">Die maximale Anzahl von Zeichen für eine einzelne OData-Prädikat zugelassen sind.</span><span class="sxs-lookup"><span data-stu-id="1d96e-103">The maximum number of characters allowed for a single OData predicate.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>