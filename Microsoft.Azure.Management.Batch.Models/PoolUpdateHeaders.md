<Type Name="PoolUpdateHeaders" FullName="Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders">
  <TypeSignature Language="C#" Value="public class PoolUpdateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUpdateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUpdateHeaders" />
  <TypeSignature Language="F#" Value="type PoolUpdateHeaders = class" />
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
            Definiert die Header für Update-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpdateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PoolUpdateHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpdateHeaders (string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders : string -&gt; Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders" Usage="new Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders eTag" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag">Der ETag-HTTP-Antwortheader. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Insbesondere können Sie das ETag an einem der If-Match- oder If-None-Match-Header übergeben.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolUpdateHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den ETag-HTTP-Antwortheader. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Insbesondere können Sie das ETag an einem der If-Match- oder If-None-Match-Header übergeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>