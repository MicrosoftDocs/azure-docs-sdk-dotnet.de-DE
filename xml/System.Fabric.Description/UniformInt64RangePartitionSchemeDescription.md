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
      <para><span data-ttu-id="88700-101">Beschreibt ein Partitionierungsschema, der ein Ganzzahlbereich gleichmäßig über eine Anzahl von Partitionen zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="88700-101">Describes a partitioning scheme where an integer range is allocated evenly across a number of partitions.</span></span></para>
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
          <para><span data-ttu-id="88700-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="88700-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> class.</span></span></para>
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
          <para><span data-ttu-id="88700-103">Die Anzahl der Partitionen in der gleichen Partitionsschema.</span><span class="sxs-lookup"><span data-stu-id="88700-103">The number of partitions in the scheme.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="88700-104">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> -Klasse durch Angabe der Anzahl der Partitionen.</span><span class="sxs-lookup"><span data-stu-id="88700-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> class by specifying the partition count.</span></span></para>
        </summary>
        <remarks><span data-ttu-id="88700-105">Der niedrige Schlüssel des Bereichs wird standardmäßig auf lang sein. "MinValue" und der hohe Schlüssel standardmäßig lang sein. "MaxValue".</span><span class="sxs-lookup"><span data-stu-id="88700-105">The low key of the range defaults to long.MinValue and the high key defaults to long.MaxValue.</span></span></remarks>
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
          <para><span data-ttu-id="88700-106">Die Anzahl der Partitionen in der gleichen Partitionsschema.</span><span class="sxs-lookup"><span data-stu-id="88700-106">The number of partitions in the scheme.</span></span></para>
        </param>
        <param name="lowKey"><span data-ttu-id="88700-107">Der niedrige Schlüssel des Bereichs.</span><span class="sxs-lookup"><span data-stu-id="88700-107">The low key of the range.</span></span></param>
        <param name="highKey"><span data-ttu-id="88700-108">Der hohe Schlüssel des Bereichs.</span><span class="sxs-lookup"><span data-stu-id="88700-108">The high key of the range.</span></span></param>
        <summary>
          <para><span data-ttu-id="88700-109">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> -Klasse durch Angabe der Anzahl der Partitionen und den Bereichswerte.</span><span class="sxs-lookup"><span data-stu-id="88700-109">Initializes a new instance of the <see cref="T:System.Fabric.Description.UniformInt64RangePartitionSchemeDescription" /> class by specifying the partition count and the range values.</span></span></para>
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
          <para><span data-ttu-id="88700-110">Ruft ab oder legt die inklusive obere Begrenzung für den Bereich von Schlüsseln, der vom Dienst unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="88700-110">Gets or sets the inclusive upper bound on the range of keys that is supported by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88700-111">Die inklusive obere Grenze des Bereichs von Schlüsseln, die vom Dienst unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="88700-111">The inclusive upper bound on the range of keys that is supported by the service.</span></span></para>
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
          <para><span data-ttu-id="88700-112">Ruft ab oder legt die inklusive untere Grenze für den Bereich von Schlüsseln, der vom Dienst unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="88700-112">Gets or sets the inclusive lower bound on the range of keys that is supported by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88700-113">Die inklusive untere Grenze des Bereichs von Schlüsseln, die vom Dienst unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="88700-113">The inclusive lower bound on the range of keys that is supported by the service.</span></span></para>
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
          <para><span data-ttu-id="88700-114">Ruft ab oder legt die Anzahl der Partitionen.</span><span class="sxs-lookup"><span data-stu-id="88700-114">Gets or sets the partition count.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88700-115">Die Anzahl der Partitionen.</span><span class="sxs-lookup"><span data-stu-id="88700-115">The partition count.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="88700-116">Gibt die Anzahl der Partitionen, die in denen dieser Dienst partitioniert ist.</span><span class="sxs-lookup"><span data-stu-id="88700-116">Specifies the number of partitions into which this service is partitioned.</span></span> <span data-ttu-id="88700-117">Jede Partition erhält ungefähr die gleiche Anzahl von Schlüsseln.</span><span class="sxs-lookup"><span data-stu-id="88700-117">Each partition receives approximately the same number of keys.</span></span> <span data-ttu-id="88700-118">Die Anzahl wird bestimmt durch Subtrahieren <languagekeyword>HighKey</languagekeyword> aus <languagekeyword>LowKey</languagekeyword> berechnet die Summe von <languagekeyword>PartitionCount</languagekeyword>.</span><span class="sxs-lookup"><span data-stu-id="88700-118">The number is determined by subtracting <languagekeyword>HighKey</languagekeyword> from <languagekeyword>LowKey</languagekeyword> and dividing the sum by <languagekeyword>PartitionCount</languagekeyword>.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>