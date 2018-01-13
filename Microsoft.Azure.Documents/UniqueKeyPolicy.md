<Type Name="UniqueKeyPolicy" FullName="Microsoft.Azure.Documents.UniqueKeyPolicy">
  <TypeSignature Language="C#" Value="public sealed class UniqueKeyPolicy : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UniqueKeyPolicy extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.UniqueKeyPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UniqueKeyPolicy&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type UniqueKeyPolicy = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein Inhaber für Richtlinien, die Eindeutigkeit für Dokumente in der Auflistung in der Azure-Cosmos-DB-Dienst angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniqueKeyPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UniqueKeyPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.UniqueKeyPolicy" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueKeys">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.UniqueKey&gt; UniqueKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.UniqueKey&gt; UniqueKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.UniqueKeyPolicy.UniqueKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property UniqueKeys As Collection(Of UniqueKey)" />
      <MemberSignature Language="F#" Value="member this.UniqueKeys : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.UniqueKey&gt; with get, set" Usage="Microsoft.Azure.Documents.UniqueKeyPolicy.UniqueKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uniqueKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.UniqueKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung von <see cref="T:Microsoft.Azure.Documents.UniqueKey" /> gewährleisten, dass die Eindeutigkeit der Dokumente in der Auflistung in der Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>