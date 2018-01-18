<Type Name="AclStatus" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AclStatus">
  <TypeSignature Language="C#" Value="public class AclStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AclStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class AclStatus" />
  <TypeSignature Language="F#" Value="type AclStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83b8f-101">Data Lake-Speicher-Datei oder Verzeichnis Access Control List Informationen.</span><span class="sxs-lookup"><span data-stu-id="83b8f-101">Data Lake Store file or directory Access Control List information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AclStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83b8f-102">Initialisiert eine neue Instanz der AclStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="83b8f-102">Initializes a new instance of the AclStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AclStatus (System.Collections.Generic.IList&lt;string&gt; entries = null, string group = null, string owner = null, Nullable&lt;int&gt; permission = null, Nullable&lt;bool&gt; stickyBit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; entries, string group, string owner, valuetype System.Nullable`1&lt;int32&gt; permission, valuetype System.Nullable`1&lt;bool&gt; stickyBit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.#ctor(System.Collections.Generic.IList{System.String},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional entries As IList(Of String) = null, Optional group As String = null, Optional owner As String = null, Optional permission As Nullable(Of Integer) = null, Optional stickyBit As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AclStatus : System.Collections.Generic.IList&lt;string&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AclStatus" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AclStatus (entries, group, owner, permission, stickyBit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entries" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="group" Type="System.String" />
        <Parameter Name="owner" Type="System.String" />
        <Parameter Name="permission" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="stickyBit" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="entries"><span data-ttu-id="83b8f-103">die Liste der ACLSpec Einträge auf eine Datei oder ein Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="83b8f-103">the list of ACLSpec entries on a file or directory.</span></span></param>
        <param name="group"><span data-ttu-id="83b8f-104">Der Gruppenbesitzer, eine AAD-Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="83b8f-104">the group owner, an AAD Object ID.</span></span></param>
        <param name="owner"><span data-ttu-id="83b8f-105">der Benutzer Besitzer, eine AAD-Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="83b8f-105">the user owner, an AAD Object ID.</span></span></param>
        <param name="permission"><span data-ttu-id="83b8f-106">Die oktale Darstellung des unbenannte Benutzers, Subnetzmaske und anderen Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="83b8f-106">The octal representation of the unnamed user, mask and other permissions.</span></span></param>
        <param name="stickyBit"><span data-ttu-id="83b8f-107">Der Indikator des gibt an, ob das sticky Bit on oder off ist.</span><span class="sxs-lookup"><span data-stu-id="83b8f-107">the indicator of whether the sticky bit is on or off.</span></span></param>
        <summary>
            <span data-ttu-id="83b8f-108">Initialisiert eine neue Instanz der AclStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="83b8f-108">Initializes a new instance of the AclStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Entries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Entries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Entries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Entries" />
      <MemberSignature Language="VB.NET" Value="Public Property Entries As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Entries : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Entries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="entries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b8f-109">Ruft ab oder legt die Liste der ACLSpec Einträge auf eine Datei oder ein Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="83b8f-109">Gets or sets the list of ACLSpec entries on a file or directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public string Group { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Group" />
      <MemberSignature Language="VB.NET" Value="Public Property Group As String" />
      <MemberSignature Language="F#" Value="member this.Group : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Group" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="group")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b8f-110">Ruft ab oder legt den Besitzer der Gruppe, eine AAD-Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="83b8f-110">Gets or sets the group owner, an AAD Object ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Owner" />
      <MemberSignature Language="VB.NET" Value="Public Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Owner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="owner")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b8f-111">Ruft ab oder legt den Besitzer der Benutzer, eine AAD-Objekt-ID.</span><span class="sxs-lookup"><span data-stu-id="83b8f-111">Gets or sets the user owner, an AAD Object ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permission">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Permission { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Permission" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Permission" />
      <MemberSignature Language="VB.NET" Value="Public Property Permission As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Permission : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.Permission" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permission")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b8f-112">Ruft ab oder legt die oktale Darstellung der unbenannten Benutzer, Maske und andere Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="83b8f-112">Gets or sets the octal representation of the unnamed user, mask and other permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StickyBit">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StickyBit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StickyBit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.StickyBit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StickyBit As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StickyBit : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AclStatus.StickyBit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stickyBit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b8f-113">Ruft den Indikator gibt an, ob das sticky Bit on oder off ist.</span><span class="sxs-lookup"><span data-stu-id="83b8f-113">Gets the indicator of whether the sticky bit is on or off.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>