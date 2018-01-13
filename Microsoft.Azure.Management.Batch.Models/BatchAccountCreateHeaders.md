<Type Name="BatchAccountCreateHeaders" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders">
  <TypeSignature Language="C#" Value="public class BatchAccountCreateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountCreateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountCreateHeaders" />
  <TypeSignature Language="F#" Value="type BatchAccountCreateHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Header für den Erstellungsvorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountCreateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BatchAccountCreateHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountCreateHeaders (string location = null, Nullable&lt;int&gt; retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, valuetype System.Nullable`1&lt;int32&gt; retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders (location, retryAfter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="retryAfter" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="location">Die URL der Ressource verwendet, um den Status des asynchronen Vorgangs zu überprüfen.</param>
        <param name="retryAfter">Vorgeschlagene Verzögerung zum Überprüfen des Status des asynchronen Vorgangs. Der Wert ist eine ganze Zahl, die die Verzögerung in Sekunden angibt.</param>
        <summary>
            Initialisiert eine neue Instanz der BatchAccountCreateHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL der Ressource verwendet, um den Status des asynchronen Vorgangs zu überprüfen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateHeaders.RetryAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Retry-After")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest vorgeschlagenen Verzögerung zum Überprüfen des Status des asynchronen Vorgangs. Der Wert ist eine ganze Zahl, die die Verzögerung in Sekunden angibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>