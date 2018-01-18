<Type Name="UserAccount" FullName="Microsoft.Azure.Batch.UserAccount">
  <TypeSignature Language="C#" Value="public class UserAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.UserAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccount" />
  <TypeSignature Language="F#" Value="type UserAccount = class&#xA;    interface ITransportObjectProvider&lt;UserAccount&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="2d450-101">Ein Benutzerkonto auf einem Azure Batch-Knoten zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="2d450-101">A user account to create on an Azure Batch node.</span></span> <span data-ttu-id="2d450-102">Tasks können so konfiguriert werden, um im Sicherheitskontext des Benutzerkontos ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2d450-102">Tasks may be configured to execute in the security context of the user account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount (string name, string password, Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel = null, Microsoft.Azure.Batch.LinuxUserConfiguration linuxUserConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string password, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; elevationLevel, class Microsoft.Azure.Batch.LinuxUserConfiguration linuxUserConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.UserAccount.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ElevationLevel},Microsoft.Azure.Batch.LinuxUserConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.UserAccount : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; * Microsoft.Azure.Batch.LinuxUserConfiguration -&gt; Microsoft.Azure.Batch.UserAccount" Usage="new Microsoft.Azure.Batch.UserAccount (name, password, elevationLevel, linuxUserConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;" />
        <Parameter Name="linuxUserConfiguration" Type="Microsoft.Azure.Batch.LinuxUserConfiguration" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="2d450-103">Der Name des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="2d450-103">The name of the user account.</span></span></param>
        <param name="password"><span data-ttu-id="2d450-104">Das Kennwort für das Benutzerkonto</span><span class="sxs-lookup"><span data-stu-id="2d450-104">The password for the user account.</span></span></param>
        <param name="elevationLevel"><span data-ttu-id="2d450-105">Die Erhöhung der Rechte Ebene des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="2d450-105">The elevation level of the user account.</span></span></param>
        <param name="linuxUserConfiguration"><span data-ttu-id="2d450-106">Zusätzliche Eigenschaften, die zum Erstellen eines Benutzerkontos auf einem Linux-Knoten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="2d450-106">Additional properties used to create a user account on a Linux node.</span></span></param>
        <summary>
            <span data-ttu-id="2d450-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.UserAccount" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2d450-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.UserAccount" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Batch.UserAccount.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d450-108">Ruft ab, oder legt diesen fest die Erhöhung der Rechte des Benutzerkontos.</span><span class="sxs-lookup"><span data-stu-id="2d450-108">Gets or sets the elevation level of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2d450-109">Wenn nicht angegeben, ist die Standardeinstellung<see cref="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" /></span><span class="sxs-lookup"><span data-stu-id="2d450-109">If omitted, the default is <see cref="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxUserConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.LinuxUserConfiguration LinuxUserConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.LinuxUserConfiguration LinuxUserConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.LinuxUserConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxUserConfiguration As LinuxUserConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxUserConfiguration : Microsoft.Azure.Batch.LinuxUserConfiguration with get, set" Usage="Microsoft.Azure.Batch.UserAccount.LinuxUserConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.LinuxUserConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d450-110">Ruft ab oder legt weitere Eigenschaften, die zum Erstellen eines Benutzerkontos auf einem Linux-Knoten verwendet.</span><span class="sxs-lookup"><span data-stu-id="2d450-110">Gets or sets additional properties used to create a user account on a Linux node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2d450-111">Diese Eigenschaft wird ignoriert, wenn für einen Windows-Pool angegeben.</span><span class="sxs-lookup"><span data-stu-id="2d450-111">This property is ignored if specified on a Windows pool.</span></span> <span data-ttu-id="2d450-112">Wenn nicht angegeben ist, wird der Benutzer mit den Standardoptionen erstellt.</span><span class="sxs-lookup"><span data-stu-id="2d450-112">If not specified, the user is created with the default options.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.UserAccount.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d450-113">Ruft ab oder legt den Namen des Benutzerkontos ein.</span><span class="sxs-lookup"><span data-stu-id="2d450-113">Gets or sets the name of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UserAccount.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.UserAccount.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d450-114">Ruft ab oder legt das Kennwort für das Benutzerkonto fest.</span><span class="sxs-lookup"><span data-stu-id="2d450-114">Gets or sets the password for the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>