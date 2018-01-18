<Type Name="AutoUserSpecification" FullName="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification">
  <TypeSignature Language="C#" Value="public class AutoUserSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoUserSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoUserSpecification" />
  <TypeSignature Language="F#" Value="type AutoUserSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e3f9a-101">Gibt die Parameter für den Auto-Benutzer, der eine Aufgabe auf die Batch-Dienst ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-101">Specifies the parameters for the auto user that runs a task on the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e3f9a-102">Initialisiert eine neue Instanz der AutoUserSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-102">Initializes a new instance of the AutoUserSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoUserSpecification (Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; scope = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; scope, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.#ctor(System.Nullable{Microsoft.Azure.Management.Batch.Models.AutoUserScope},System.Nullable{Microsoft.Azure.Management.Batch.Models.ElevationLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional scope As Nullable(Of AutoUserScope) = null, Optional elevationLevel As Nullable(Of ElevationLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.AutoUserSpecification : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; -&gt; Microsoft.Azure.Management.Batch.Models.AutoUserSpecification" Usage="new Microsoft.Azure.Management.Batch.Models.AutoUserSpecification (scope, elevationLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scope" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt;" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="scope"><span data-ttu-id="e3f9a-103">Der Bereich für den Benutzer automatisch</span><span class="sxs-lookup"><span data-stu-id="e3f9a-103">The scope for the auto user</span></span></param>
        <param name="elevationLevel"><span data-ttu-id="e3f9a-104">Die Ebene der Erhöhung der Rechte des Benutzers automatisch.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-104">The elevation level of the auto user.</span></span></param>
        <summary>
            <span data-ttu-id="e3f9a-105">Initialisiert eine neue Instanz der AutoUserSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-105">Initializes a new instance of the AutoUserSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3f9a-106">Ruft ab oder legt die Ebene der Erhöhung der Rechte des Benutzers automatisch.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-106">Gets or sets the elevation level of the auto user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e3f9a-107">NonAdmin - der Auto-Benutzer ist ein Standardbenutzer ohne erhöhte Zugriffsrechte.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-107">nonAdmin - The auto user is a standard user without elevated access.</span></span> <span data-ttu-id="e3f9a-108">Admin - der Auto-Benutzer ist ein Benutzer mit erweiterten Zugriff und arbeitet mit vollständigen Administratorberechtigungen.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-108">admin - The auto user is a user with elevated access and operates with full Administrator permissions.</span></span> <span data-ttu-id="e3f9a-109">Der Standardwert ist NonAdmin.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-109">The default value is nonAdmin.</span></span> <span data-ttu-id="e3f9a-110">Folgende Werte sind möglich: "NonAdmin", "Admin"</span><span class="sxs-lookup"><span data-stu-id="e3f9a-110">Possible values include: 'NonAdmin', 'Admin'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As Nullable(Of AutoUserScope)" />
      <MemberSignature Language="F#" Value="member this.Scope : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoUserSpecification.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AutoUserScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3f9a-111">Ruft ab oder legt den Bereich für den Benutzer automatisch</span><span class="sxs-lookup"><span data-stu-id="e3f9a-111">Gets or sets the scope for the auto user</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e3f9a-112">Speicherpool: Gibt an, dass der Task als das allgemeine Auto-Benutzerkonto ausgeführt wird, die auf jedem Knoten in einem Pool erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-112">pool - specifies that the task runs as the common auto user account which is created on every node in a pool.</span></span> <span data-ttu-id="e3f9a-113">Aufgabe: Gibt an, dass der Dienst einen neuen Benutzer für den Task erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-113">task - specifies that the service should create a new user for the task.</span></span> <span data-ttu-id="e3f9a-114">Der Standardwert ist die Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="e3f9a-114">The default value is task.</span></span> <span data-ttu-id="e3f9a-115">Folgende Werte sind möglich: "Aufgabe", "Pool"</span><span class="sxs-lookup"><span data-stu-id="e3f9a-115">Possible values include: 'Task', 'Pool'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>