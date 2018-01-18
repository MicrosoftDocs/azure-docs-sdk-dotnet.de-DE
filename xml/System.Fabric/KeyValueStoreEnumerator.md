<Type Name="KeyValueStoreEnumerator" FullName="System.Fabric.KeyValueStoreEnumerator">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreEnumerator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreEnumerator extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreEnumerator" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreEnumerator" />
  <TypeSignature Language="F#" Value="type KeyValueStoreEnumerator = class" />
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
      <span data-ttu-id="73f2d-101"><para>Liest den Inhalt der lokalen Speicher eines sekundären Replikats, innerhalb des Kontexts eines Rückrufs Abschluss kopieren. </para>
      <seealso cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />.</span><span class="sxs-lookup"><span data-stu-id="73f2d-101"><para>Reads the local store contents of a secondary replica within the context of a copy completion callback.</para>
            <seealso cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />.</span></span>
</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.Enumerate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enumerate (keyPrefix As String) As IEnumerator(Of KeyValueStoreItem)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreEnumerator.Enumerate keyPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para><span data-ttu-id="73f2d-102">Gibt einen optionalen Filter an Schlüssel-Präfix, während der Enumeration anwenden.</span><span class="sxs-lookup"><span data-stu-id="73f2d-102">Specifies an optional key-prefix filter to apply during enumeration.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="73f2d-103">Listet den Inhalt der lokalen Speicher und enthält den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="73f2d-103">Enumerates the local store contents and includes the data value for all enumerated key-value pairs.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="73f2d-104">Ein Enumerator für den Inhalt der lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="73f2d-104">An enumerator over the local store contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.Enumerate(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enumerate (keyPrefix As String, strictPrefix As Boolean) As IEnumerator(Of KeyValueStoreItem)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreEnumerator.Enumerate (keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para><span data-ttu-id="73f2d-105">Gibt einen optionalen Filter an Schlüssel-Präfix, während der Enumeration anwenden.</span><span class="sxs-lookup"><span data-stu-id="73f2d-105">Specifies an optional key-prefix filter to apply during enumeration.</span></span></para>
        </param>
        <param name="strictPrefix">
          <para><span data-ttu-id="73f2d-106">Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="73f2d-106">When true, only keys prefixed by the value specified for <b>keyPrefix</b> are returned.</span></span> <span data-ttu-id="73f2d-107">Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind.</span><span class="sxs-lookup"><span data-stu-id="73f2d-107">Otherwise, enumeration starts at the first key matching or lexicographically greater than <b>keyPrefix</b> and continues until there are no more keys.</span></span> <span data-ttu-id="73f2d-108">Der Standardwert ist <b>True</b>.</span><span class="sxs-lookup"><span data-stu-id="73f2d-108">The default is <b>true</b>.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="73f2d-109">Listet den Inhalt der lokalen Speicher und enthält den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="73f2d-109">Enumerates the local store contents and includes the data value for all enumerated key-value pairs.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="73f2d-110">Ein Enumerator für den Inhalt der lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="73f2d-110">An enumerator over the local store contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.EnumerateMetadata(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateMetadata (keyPrefix As String) As IEnumerator(Of KeyValueStoreItemMetadata)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreEnumerator.EnumerateMetadata keyPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para><span data-ttu-id="73f2d-111">Gibt eine optionale präfixfilter während der Enumeration anwenden.</span><span class="sxs-lookup"><span data-stu-id="73f2d-111">Specifies an optional prefix filter to apply during enumeration.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="73f2d-112">Listet den Inhalt der lokalen Speicher, aber schließt den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="73f2d-112">Enumerates the local store contents but excludes the data value for all enumerated key-value pairs.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="73f2d-113">Ein Enumerator für den Inhalt der lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="73f2d-113">An enumerator over the local store contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.EnumerateMetadata(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateMetadata (keyPrefix As String, strictPrefix As Boolean) As IEnumerator(Of KeyValueStoreItemMetadata)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreEnumerator.EnumerateMetadata (keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para><span data-ttu-id="73f2d-114">Gibt einen optionalen Filter an Schlüssel-Präfix, während der Enumeration anwenden.</span><span class="sxs-lookup"><span data-stu-id="73f2d-114">Specifies an optional key-prefix filter to apply during enumeration.</span></span></para>
        </param>
        <param name="strictPrefix">
          <para><span data-ttu-id="73f2d-115">Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="73f2d-115">When true, only keys prefixed by the value specified for <b>keyPrefix</b> are returned.</span></span> <span data-ttu-id="73f2d-116">Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind.</span><span class="sxs-lookup"><span data-stu-id="73f2d-116">Otherwise, enumeration starts at the first key matching or lexicographically greater than <b>keyPrefix</b> and continues until there are no more keys.</span></span> <span data-ttu-id="73f2d-117">Der Standardwert ist <b>True</b>.</span><span class="sxs-lookup"><span data-stu-id="73f2d-117">The default is <b>true</b>.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="73f2d-118">Listet den Inhalt der lokalen Speicher, aber schließt den Datenwert für alle Schlüssel-Wert-Paare aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="73f2d-118">Enumerates the local store contents but excludes the data value for all enumerated key-value pairs.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="73f2d-119">Ein Enumerator für den Inhalt der lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="73f2d-119">An enumerator over the local store contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>