<Type Name="UniformInt64RangePartitionSchemeDescription" FullName="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription">
  <TypeSignature Language="C#" Value="public sealed class UniformInt64RangePartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UniformInt64RangePartitionSchemeDescription extends System.Fabric.Description.PartitionSchemeDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UniformInt64RangePartitionSchemeDescription&#xA;Inherits PartitionSchemeDescription" />
  <TypeSignature Language="F#" Value="type UniformInt64RangePartitionSchemeDescription = class&#xA;    inherit PartitionSchemeDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.PartitionSchemeDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt ein Partitionierungsschema, der ein Ganzzahlbereich gleichmäßig über eine Anzahl von Partitionen zugeordnet ist.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription (int partitionCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 partitionCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionCount As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription : int -&gt; System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" Usage="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription partitionCount" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="partitionCount">
          <para>Die Anzahl der Partitionen in der gleichen Partitionsschema.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> -Klasse durch Angabe der Anzahl der Partitionen.</para>
        </summary>
        <remarks>Der niedrige Schlüssel des Bereichs wird standardmäßig auf lang sein. "MinValue" und der hohe Schlüssel standardmäßig lang sein. "MaxValue".</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniformInt64RangePartitionSchemeDescription (int partitionCount, long lowKey, long highKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 partitionCount, int64 lowKey, int64 highKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.#ctor(System.Int32,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionCount As Integer, lowKey As Long, highKey As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription : int * int64 * int64 -&gt; System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" Usage="new System.Fabric.Description.UniformInt64RangePartitionSchemeDescription (partitionCount, lowKey, highKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionCount" Type="System.Int32" />
        <Parameter Name="lowKey" Type="System.Int64" />
        <Parameter Name="highKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionCount">
          <para>Die Anzahl der Partitionen in der gleichen Partitionsschema.</para>
        </param>
        <param name="lowKey">Der niedrige Schlüssel des Bereichs.</param>
        <param name="highKey">Der hohe Schlüssel des Bereichs.</param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> -Klasse durch Angabe der Anzahl der Partitionen und den Bereichswerte.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighKey">
      <MemberSignature Language="C#" Value="public long HighKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HighKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.HighKey" />
      <MemberSignature Language="VB.NET" Value="Public Property HighKey As Long" />
      <MemberSignature Language="F#" Value="member this.HighKey : int64 with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.HighKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die inklusive obere Begrenzung für den Bereich von Schlüsseln, der vom Dienst unterstützt wird.</para>
        </summary>
        <value>
          <para>Die inklusive obere Grenze des Bereichs von Schlüsseln, die vom Dienst unterstützt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowKey">
      <MemberSignature Language="C#" Value="public long LowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LowKey" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.LowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property LowKey As Long" />
      <MemberSignature Language="F#" Value="member this.LowKey : int64 with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.LowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die inklusive untere Grenze für den Bereich von Schlüsseln, der vom Dienst unterstützt wird.</para>
        </summary>
        <value>
          <para>Die inklusive untere Grenze des Bereichs von Schlüsseln, die vom Dienst unterstützt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public int PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PartitionCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : int with get, set" Usage="System.Fabric.Description.UniformInt64RangePartitionSchemeDescription.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Anzahl der Partitionen.</para>
        </summary>
        <value>
          <para>Die Anzahl der Partitionen.</para>
        </value>
        <remarks>
          <para>Gibt die Anzahl der Partitionen, die in denen dieser Dienst partitioniert ist. Jede Partition erhält ungefähr die gleiche Anzahl von Schlüsseln. Die Anzahl wird bestimmt durch Subtrahieren <languagekeyword>HighKey</languagekeyword> aus <languagekeyword>LowKey</languagekeyword> berechnet die Summe von <languagekeyword>PartitionCount</languagekeyword>.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>