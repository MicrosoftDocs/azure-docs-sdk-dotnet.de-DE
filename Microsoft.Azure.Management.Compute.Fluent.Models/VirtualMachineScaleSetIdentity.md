<Type Name="VirtualMachineScaleSetIdentity" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetIdentity" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetIdentity = class" />
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
            Die Identität für die VM-Skalierungsgruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetIdentity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetIdentity (string principalId = null, string tenantId = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string principalId, string tenantId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As String = null, Optional tenantId As String = null, Optional type As Nullable(Of ResourceIdentityType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity : string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity (principalId, tenantId, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId">Der Datenbankprinzipal-Id des VM-Skalierungsgruppe festlegen Identität.</param>
        <param name="tenantId">Legen Sie die Mandanten-Id, die der VM-Skalierungsgruppe zugeordnet.</param>
        <param name="type">Der Typ der Identität, die für die VM-Skalierungsgruppe verwendet gesetzt. Derzeit ist der einzige unterstützte Typ "SystemAssigned", die eine Identität implizit erstellt. Folgende Werte sind möglich: "SystemAssigned"</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetIdentity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public string PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="principalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Prinzipal-Id der VM-Skalierungsgruppe festgelegten Identität.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Mandanten-Id, die der VM-Skalierungsgruppe zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ResourceIdentityType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ResourceIdentityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Identität, die für die VM-Skalierungsgruppe verwendet. Derzeit ist der einzige unterstützte Typ "SystemAssigned", die eine Identität implizit erstellt. Folgende Werte sind möglich: "SystemAssigned"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>