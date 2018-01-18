<Type Name="UpgradePolicy" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy">
  <TypeSignature Language="C#" Value="public class UpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpgradePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class UpgradePolicy" />
  <TypeSignature Language="F#" Value="type UpgradePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4098d-101">Beschreibt eine Upgraderichtlinie - automatische oder manuelle.</span><span class="sxs-lookup"><span data-stu-id="4098d-101">Describes an upgrade policy - automatic or manual.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4098d-102">Initialisiert eine neue Instanz der UpgradePolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4098d-102">Initializes a new instance of the UpgradePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpgradePolicy (Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt; mode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt; mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional mode As Nullable(Of UpgradeMode) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy mode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mode" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt;" />
      </Parameters>
      <Docs>
        <param name="mode"><span data-ttu-id="4098d-103">Der Upgrade-Modus.</span><span class="sxs-lookup"><span data-stu-id="4098d-103">The upgrade mode.</span></span> <span data-ttu-id="4098d-104">Folgende Werte sind möglich: 'Automatic', 'Manual'</span><span class="sxs-lookup"><span data-stu-id="4098d-104">Possible values include: 'Automatic', 'Manual'</span></span></param>
        <summary>
            <span data-ttu-id="4098d-105">Initialisiert eine neue Instanz der UpgradePolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4098d-105">Initializes a new instance of the UpgradePolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt; Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt; Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As Nullable(Of UpgradeMode)" />
      <MemberSignature Language="F#" Value="member this.Mode : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.UpgradePolicy.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4098d-106">Abrufen oder Festlegen der Upgrademodus.</span><span class="sxs-lookup"><span data-stu-id="4098d-106">Gets or sets the upgrade mode.</span></span> <span data-ttu-id="4098d-107">Folgende Werte sind möglich: 'Automatic', 'Manual'</span><span class="sxs-lookup"><span data-stu-id="4098d-107">Possible values include: 'Automatic', 'Manual'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>