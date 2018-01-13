<Type Name="PartitionLoadInformation" FullName="System.Fabric.Query.PartitionLoadInformation">
  <TypeSignature Language="C#" Value="public class PartitionLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.PartitionLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionLoadInformation" />
  <TypeSignature Language="F#" Value="type PartitionLoadInformation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die Informationen zur Partition geladen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.PartitionLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine Instanz der <see cref="T:System.Fabric.Query.PartitionLoadInformation" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PartitionLoadInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Query.PartitionLoadInformation.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Partitions-ID. Mit diesem Befehl kann als Piping Zweck verwendet werden.</para>
        </summary>
        <value>
          <para>Die Partitions-ID.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryLoadMetricReports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; PrimaryLoadMetricReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; PrimaryLoadMetricReports" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PartitionLoadInformation.PrimaryLoadMetricReports" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryLoadMetricReports As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.PrimaryLoadMetricReports : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.PartitionLoadInformation.PrimaryLoadMetricReports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der Auslastungstest-Berichte für primäre Rolle dieser Partition ab.</para>
        </summary>
        <value>
          <para>Die Liste der Auslastungstest-Berichte für primäre Rolle dieser Partition.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryLoadMetricReports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; SecondaryLoadMetricReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; SecondaryLoadMetricReports" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PartitionLoadInformation.SecondaryLoadMetricReports" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryLoadMetricReports As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.SecondaryLoadMetricReports : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.PartitionLoadInformation.SecondaryLoadMetricReports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der Auslastungstest-Berichte für sekundäre Rolle von dieser Partition ab.</para>
        </summary>
        <value>
          <para>Die Liste der Auslastungstest-Berichte für sekundäre Rolle von dieser Partition.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>