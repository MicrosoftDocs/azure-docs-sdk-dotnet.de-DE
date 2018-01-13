<Type Name="VirtualMachineScaleSetSkuCapacity" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetSkuCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetSkuCapacity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetSkuCapacity" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetSkuCapacity = class" />
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
            Beschreibt, von einer Sku Skalierungsinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetSkuCapacity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetSkuCapacity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetSkuCapacity (Nullable&lt;long&gt; minimum = null, Nullable&lt;long&gt; maximum = null, Nullable&lt;long&gt; defaultCapacity = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt; scaleType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; minimum, valuetype System.Nullable`1&lt;int64&gt; maximum, valuetype System.Nullable`1&lt;int64&gt; defaultCapacity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt; scaleType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional minimum As Nullable(Of Long) = null, Optional maximum As Nullable(Of Long) = null, Optional defaultCapacity As Nullable(Of Long) = null, Optional scaleType As Nullable(Of VirtualMachineScaleSetSkuScaleType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity (minimum, maximum, defaultCapacity, scaleType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="defaultCapacity" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="scaleType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt;" />
      </Parameters>
      <Docs>
        <param name="minimum">Die Mindestkapazität.</param>
        <param name="maximum">Die maximale Kapazität, die festgelegt werden kann.</param>
        <param name="defaultCapacity">Die Standardkapazität.</param>
        <param name="scaleType">Der Typ der für die Sku.
            Folgende Werte sind möglich: "Automatisch", "None"</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineScaleSetSkuCapacity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultCapacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DefaultCapacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DefaultCapacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.DefaultCapacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultCapacity As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DefaultCapacity : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.DefaultCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultCapacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die festgelegte Standardkapazität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Maximum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Maximum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Kapazität, die festgelegt werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Minimum { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Minimum As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die minimale Kapazität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt; ScaleType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt; ScaleType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.ScaleType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScaleType As Nullable(Of VirtualMachineScaleSetSkuScaleType)" />
      <MemberSignature Language="F#" Value="member this.ScaleType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuCapacity.ScaleType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scaleType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetSkuScaleType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Skalierung-Typ ab, für die Sku. Folgende Werte sind möglich: "Automatisch", "None"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>