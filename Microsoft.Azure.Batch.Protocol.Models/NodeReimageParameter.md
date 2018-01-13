<Type Name="NodeReimageParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter">
  <TypeSignature Language="C#" Value="public class NodeReimageParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeReimageParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeReimageParameter" />
  <TypeSignature Language="F#" Value="type NodeReimageParameter = class" />
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
            Optionen für die erneute imageerstellung Compute-Knoten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeReimageParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NodeReimageParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeReimageParameter (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nodeReimageOption As Nullable(Of ComputeNodeReimageOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter nodeReimageOption" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeReimageOption">Wann reimaging dem Computeknoten und was mit den derzeit ausgeführten Tasks geschehen.</param>
        <summary>
            Initialisiert eine neue Instanz der NodeReimageParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReimageOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; NodeReimageOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; NodeReimageOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.NodeReimageOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeReimageOption As Nullable(Of ComputeNodeReimageOption)" />
      <MemberSignature Language="F#" Value="member this.NodeReimageOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeReimageParameter.NodeReimageOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeReimageOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wann die Serverknoten reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>