<Type Name="PartitionKey" FullName="Microsoft.Azure.Documents.PartitionKey">
  <TypeSignature Language="C#" Value="public sealed class PartitionKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.PartitionKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionKey" />
  <TypeSignature Language="F#" Value="type PartitionKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Partition-Schlüssel-Wert, der die Zielpartition einer Auflistung in der Azure-Cosmos-DB-Dienst identifiziert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionKey (object keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyValue As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.PartitionKey : obj -&gt; Microsoft.Azure.Documents.PartitionKey" Usage="new Microsoft.Azure.Documents.PartitionKey keyValue" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="keyValue">
            Der Wert der Dokumenteigenschaft, die als Partitionsschlüssel angegeben wird, wenn eine Auflistung erstellt wird.
            </param>
        <summary>
            Instanziiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.PartitionKey" /> Objekt.
            </summary>
        <remarks>
            Diese Klasse stellt einen Partition-Schlüssel-Wert, der die Zielpartition einer Auflistung in der Azure-Cosmos-DB-Dienst identifiziert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="partitionKey.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other">Das zu vergleichende Objekt.</param>
        <summary>
            Überschreibt den Gleichheitsoperator für Objektvergleiche zwischen zwei Instanzen von <see cref="T:Microsoft.Azure.Documents.PartitionKey" />.
            </summary>
        <returns>"True", wenn zwei Objektinstanz als gleich betrachtet werden.</returns>
        <remarks>
            Diese Klasse stellt einen Partition-Schlüssel-Wert, der die Zielpartition einer Auflistung in der Azure-Cosmos-DB-Dienst identifiziert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FromJsonString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.PartitionKey FromJsonString (string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.PartitionKey FromJsonString(string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.FromJsonString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FromJsonString (keyValue As String) As PartitionKey" />
      <MemberSignature Language="F#" Value="static member FromJsonString : string -&gt; Microsoft.Azure.Documents.PartitionKey" Usage="Microsoft.Azure.Documents.PartitionKey.FromJsonString keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue">
            Der Wert der Dokumenteigenschaft, die als Partitionsschlüssel angegeben wird, wenn eine Auflistung, in die serialisierte JSON-Format erstellt wird.
            </param>
        <summary>
            Instanziiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.PartitionKey" /> Objekt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Diese Klasse stellt einen Partition-Schlüssel-Wert, der die Zielpartition einer Auflistung in der Azure-Cosmos-DB-Dienst identifiziert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="partitionKey.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Hashfunktion, die den Hashcode für das Objekt zurückgeben.
            </summary>
        <returns>Der Hashcode für diese <see cref="T:Microsoft.Azure.Documents.PartitionKey" /> Instanz</returns>
        <remarks>
            Diese Klasse stellt einen Partition-Schlüssel-Wert, der die Zielpartition einer Auflistung in der Azure-Cosmos-DB-Dienst identifiziert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überschreiben Sie die Basis ToString-Methode, um die Ausgabe des Werts der einzelnen Schlüsselkomponente, getrennt durch ein Leerzeichen an.
            </summary>
        <returns>Die Zeichenfolgendarstellung aller Werte für die zentrale Komponente.</returns>
        <remarks>
            Diese Klasse stellt einen Partition-Schlüssel-Wert, der die Zielpartition einer Auflistung in der Azure-Cosmos-DB-Dienst identifiziert.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>