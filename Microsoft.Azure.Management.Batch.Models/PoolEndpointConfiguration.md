<Type Name="PoolEndpointConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration">
  <TypeSignature Language="C#" Value="public class PoolEndpointConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEndpointConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEndpointConfiguration" />
  <TypeSignature Language="F#" Value="type PoolEndpointConfiguration = class" />
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
            Die Endpunktkonfiguration für einen Pool.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PoolEndpointConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEndpointConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; inboundNatPools);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; inboundNatPools) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.InboundNatPool})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inboundNatPools As IList(Of InboundNatPool))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; -&gt; Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration inboundNatPools" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt;" />
      </Parameters>
      <Docs>
        <param name="inboundNatPools">Eine Liste der eingehenden NAT-Pools, die verwendet werden kann, um bestimmte Ports auf einem einzelnen Serverknoten extern zu behandeln.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolEndpointConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; InboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatPools As IList(Of InboundNatPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.InboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der eingehenden NAT-Pools, die verwendet werden kann, um bestimmte Ports auf einem einzelnen Serverknoten extern zu behandeln.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die maximale Anzahl von eingehenden NAT-Pools pro Batch-Pool ist 5. Wenn die maximale Anzahl von eingehenden NAT-Pools überschritten, wird die Anforderung mit HTTP-Statuscode 400 schlägt fehl.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolEndpointConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>