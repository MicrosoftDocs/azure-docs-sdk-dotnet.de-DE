<Type Name="NodeId" FullName="System.Fabric.NodeId">
  <TypeSignature Language="C#" Value="public class NodeId" />
  <TypeSignature Language="ILAsm" Value=".class public ansi beforefieldinit NodeId extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeId" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeId" />
  <TypeSignature Language="F#" Value="type NodeId = class" />
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
      <para><span data-ttu-id="7ffe3-101">Klasse zum Kapseln von einer Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-101">Class to encapsulate a node ID.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeId (System.Numerics.BigInteger high, System.Numerics.BigInteger low);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Numerics.BigInteger high, valuetype System.Numerics.BigInteger low) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.#ctor(System.Numerics.BigInteger,System.Numerics.BigInteger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (high As BigInteger, low As BigInteger)" />
      <MemberSignature Language="F#" Value="new System.Fabric.NodeId : System.Numerics.BigInteger * System.Numerics.BigInteger -&gt; System.Fabric.NodeId" Usage="new System.Fabric.NodeId (high, low)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="high" Type="System.Numerics.BigInteger" />
        <Parameter Name="low" Type="System.Numerics.BigInteger" />
      </Parameters>
      <Docs>
        <param name="high">
          <para><span data-ttu-id="7ffe3-102">Die höherwertigen-Komponente von der <see cref="T:System.Fabric.NodeId" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-102">The high order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </param>
        <param name="low">
          <para><span data-ttu-id="7ffe3-103">Die Komponente das untere die <see cref="T:System.Fabric.NodeId" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-103">The low order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7ffe3-104">Initialisiert eine neue <see cref="T:System.Fabric.NodeId" /> Objekt, mit der angegebenen oberen und unteren Komponenten zu bestellen.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-104">Initializes a new <see cref="T:System.Fabric.NodeId" /> object, with the specified high and low order components.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="nodeId.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">
          <para><span data-ttu-id="7ffe3-105">Das Objekt, das mit der aktuellen <see cref="T:System.Fabric.NodeId" /> verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-105">The object to compare with the current <see cref="T:System.Fabric.NodeId" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7ffe3-106">Gibt an, ob dies <see cref="T:System.Fabric.NodeId" /> Objekt und das angegebene Objekt gleich sind.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-106">Indicates whether this <see cref="T:System.Fabric.NodeId" /> object and the specified object are equal.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7ffe3-107">Gibt eine <see cref="T:System.Boolean" /> Wert, der <languageKeyword>"true"</languageKeyword> , wenn die Objekte denselben Typ aufweisen und denselben Wert darstellen andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-107">Returns a <see cref="T:System.Boolean" /> value that is <languageKeyword>true</languageKeyword> if the objects are the same type and represent the same value; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="nodeId.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7ffe3-108">Gibt den Hashcode für dieses <see cref="T:System.Fabric.NodeId" />-Objekt zurück.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-108">Returns the hash code for this <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7ffe3-109">Ein 32-Bit-Hashcode als ganze Zahl mit Vorzeichen.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-109">A 32-bit signed integer hash code.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger High" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeId.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As BigInteger" />
      <MemberSignature Language="F#" Value="member this.High : System.Numerics.BigInteger" Usage="System.Fabric.NodeId.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7ffe3-110">Die höherwertigen-Komponente von der <see cref="T:System.Fabric.NodeId" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-110">The high order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7ffe3-111">Gibt <see cref="T:System.Numerics.BigInteger" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-111">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger Low" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeId.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As BigInteger" />
      <MemberSignature Language="F#" Value="member this.Low : System.Numerics.BigInteger" Usage="System.Fabric.NodeId.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7ffe3-112">Die Komponente das untere die <see cref="T:System.Fabric.NodeId" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-112">The low order component of the <see cref="T:System.Fabric.NodeId" /> object.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7ffe3-113">Gibt <see cref="T:System.Numerics.BigInteger" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-113">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (System.Fabric.NodeId value1, System.Fabric.NodeId value2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class System.Fabric.NodeId value1, class System.Fabric.NodeId value2) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.op_Equality(System.Fabric.NodeId,System.Fabric.NodeId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (value1 As NodeId, value2 As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : System.Fabric.NodeId * System.Fabric.NodeId -&gt; bool" Usage="value1 = value2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value1" Type="System.Fabric.NodeId" />
        <Parameter Name="value2" Type="System.Fabric.NodeId" />
      </Parameters>
      <Docs>
        <param name="value1">
          <para><span data-ttu-id="7ffe3-114">Ein <see cref="T:System.Fabric.NodeId" /> zu vergleichende Objekt <paramref name="value2" />.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-114">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value2" />.</span></span></para>
        </param>
        <param name="value2">
          <para><span data-ttu-id="7ffe3-115">Ein <see cref="T:System.Fabric.NodeId" /> zu vergleichende Objekt <paramref name="value1" />.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-115">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value1" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7ffe3-116">Bestimmt, ob zwei <see cref="T:System.Fabric.NodeId" />-Objekte denselben Wert haben.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-116">Determines whether two <see cref="T:System.Fabric.NodeId" /> objects have the same value.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7ffe3-117">Gibt eine <see cref="T:System.Boolean" /> Wert, der <languageKeyword>"true"</languageKeyword> Wenn die Objekte, entspricht; andernfalls sind <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-117">Returns a <see cref="T:System.Boolean" /> value that is <languageKeyword>true</languageKeyword> if the objects are equivalent; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (System.Fabric.NodeId value1, System.Fabric.NodeId value2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class System.Fabric.NodeId value1, class System.Fabric.NodeId value2) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.op_Inequality(System.Fabric.NodeId,System.Fabric.NodeId)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (value1 As NodeId, value2 As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : System.Fabric.NodeId * System.Fabric.NodeId -&gt; bool" Usage="System.Fabric.NodeId.op_Inequality (value1, value2)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value1" Type="System.Fabric.NodeId" />
        <Parameter Name="value2" Type="System.Fabric.NodeId" />
      </Parameters>
      <Docs>
        <param name="value1">
          <para><span data-ttu-id="7ffe3-118">Ein <see cref="T:System.Fabric.NodeId" /> zu vergleichende Objekt <paramref name="value2" />.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-118">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value2" />.</span></span></para>
        </param>
        <param name="value2">
          <para><span data-ttu-id="7ffe3-119">Ein <see cref="T:System.Fabric.NodeId" /> zu vergleichende Objekt <paramref name="value1" />.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-119">A <see cref="T:System.Fabric.NodeId" /> object to compare with <paramref name="value1" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7ffe3-120">Bestimmt, ob zwei <see cref="T:System.Fabric.NodeId" /> -Objekte verschiedene Werte haben.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-120">Determines whether two <see cref="T:System.Fabric.NodeId" /> objects have different values.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7ffe3-121">Gibt eine <see cref="T:System.Boolean" /> Wert, der <languageKeyword>"true"</languageKeyword> die Objekte besitzen unterschiedliche Werte; andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-121">Returns a <see cref="T:System.Boolean" /> value that is <languageKeyword>true</languageKeyword> if the objects have different values; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeId.ToString " />
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
          <para><span data-ttu-id="7ffe3-122">Erstellt und gibt eine Zeichenfolgendarstellung der aktuellen Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-122">Creates and returns a string representation of the current node ID.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7ffe3-123">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-123">Returns <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string from, out System.Fabric.NodeId parsedNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string from, [out] class System.Fabric.NodeId&amp; parsedNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeId.TryParse(System.String,System.Fabric.NodeId@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (from As String, ByRef parsedNodeId As NodeId) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="System.Fabric.NodeId.TryParse (from, parsedNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.String" />
        <Parameter Name="parsedNodeId" Type="System.Fabric.NodeId&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="from">
          <para><span data-ttu-id="7ffe3-124">Eine Zeichenfolge, enthält der Knoten-ID zu konvertieren.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-124">A string containing the node ID to convert.</span></span></para>
        </param>
        <param name="parsedNodeId">
          <para><span data-ttu-id="7ffe3-125">Enthält bei Rückgabe dieser Methode ein neues <see cref="T:System.Fabric.NodeId" /> Objekt entspricht der ID in enthaltenen Knoten <paramref name="from" />, wenn die Konvertierung erfolgreich war, oder <languageKeyword>null</languageKeyword> bei einem Konvertierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-125">When this method returns, contains a new <see cref="T:System.Fabric.NodeId" /> object equivalent to the node ID contained in <paramref name="from" />, if the conversion succeeded, or <languageKeyword>null</languageKeyword> if the conversion failed.</span></span> <span data-ttu-id="7ffe3-126">Dieser Parameter wird nicht initialisiert übergeben.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-126">This parameter is passed uninitialized.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7ffe3-127">Konvertiert die Zeichenfolgendarstellung eine Knoten-ID, um seine <see cref="T:System.Fabric.NodeId" /> Objekt entspricht.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-127">Converts the string representation of a node ID to its <see cref="T:System.Fabric.NodeId" /> object equivalent.</span></span> <span data-ttu-id="7ffe3-128">Ein Rückgabewert gibt an, ob der Vorgang erfolgreich abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-128">A return value indicates whether the operation succeeded.</span></span></para>
        </summary>
        <returns>
          <returns><span data-ttu-id="7ffe3-129">Ein boolescher Wert, der angibt, ob die Analyse erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="7ffe3-129">A boolean indicating if the parse was successful</span></span></returns>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>