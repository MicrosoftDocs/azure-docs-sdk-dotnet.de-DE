<Type Name="PartitionStrategy+Builder" FullName="Microsoft.Azure.Graphs.PartitionStrategy+Builder">
  <TypeSignature Language="C#" Value="public sealed class PartitionStrategy.Builder" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit PartitionStrategy/Builder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.PartitionStrategy.Builder" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionStrategy.Builder" />
  <TypeSignature Language="F#" Value="type PartitionStrategy.Builder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Generatorklasse für Partitionsstrategie 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Builder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            -Generator-Methode
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.Create" />
      <MemberSignature Language="VB.NET" Value="Public Function Create () As PartitionStrategy" />
      <MemberSignature Language="F#" Value="member this.Create : unit -&gt; Microsoft.Azure.Graphs.PartitionStrategy" Usage="builder.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt das PartitionStrategy-Objekt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy.Builder PartitionKey (string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy/Builder PartitionKey(string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.PartitionKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function PartitionKey (partitionKey As String) As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="builder.PartitionKey partitionKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey">To be added.</param>
        <summary>
            Gibt den Namen der Partition an.  Dies ist der Schlüssel, der den Partitionswert enthält. 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyString">
      <MemberSignature Language="C#" Value="public string PartitionKeyString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.PartitionStrategy.Builder.PartitionKeyString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyString As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyString : string" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Builder.PartitionKeyString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Getter und Setter für PartitionKey-Name
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPartitions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy.Builder ReadPartitions (params object[] readPartitions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy/Builder ReadPartitions(object[] readPartitions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.ReadPartitions(System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPartitions (ParamArray readPartitions As Object()) As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="member this.ReadPartitions : obj[] -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="builder.ReadPartitions readPartitions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="readPartitions" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="readPartitions">To be added.</param>
        <summary>
            Gibt die Partition des Diagramms zum Auslesen.  Es ist möglich, mehrere partitionsschlüsseln um Lesen aus mehreren Partitionen gleichzeitig zuzuweisen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPartitionSet">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.HashSet&lt;object&gt; ReadPartitionSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.HashSet`1&lt;object&gt; ReadPartitionSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.PartitionStrategy.Builder.ReadPartitionSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadPartitionSet As HashSet(Of Object)" />
      <MemberSignature Language="F#" Value="member this.ReadPartitionSet : System.Collections.Generic.HashSet&lt;obj&gt;" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Builder.ReadPartitionSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.HashSet&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Getter und Setter für ReadPartition festlegen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePartition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.PartitionStrategy.Builder WritePartition (object writePartition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.PartitionStrategy/Builder WritePartition(object writePartition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.PartitionStrategy.Builder.WritePartition(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WritePartition (writePartition As Object) As PartitionStrategy.Builder" />
      <MemberSignature Language="F#" Value="member this.WritePartition : obj -&gt; Microsoft.Azure.Graphs.PartitionStrategy.Builder" Usage="builder.WritePartition writePartition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.PartitionStrategy+Builder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writePartition" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="writePartition">To be added.</param>
        <summary>
             Gibt den Namen der Partition, die beim Hinzufügen von Scheitelpunkte, Ränder und Vertex-Eigenschaften zu schreiben.  Dieser Name kann es sich um einen benutzerdefinierten Wert annehmen. Es ist nur möglich, zu einem Zeitpunkt auf eine einzelne Partition zu schreiben.
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritePartitionObject">
      <MemberSignature Language="C#" Value="public object WritePartitionObject { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object WritePartitionObject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.PartitionStrategy.Builder.WritePartitionObject" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WritePartitionObject As Object" />
      <MemberSignature Language="F#" Value="member this.WritePartitionObject : obj" Usage="Microsoft.Azure.Graphs.PartitionStrategy.Builder.WritePartitionObject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Getter und Setter für WritePartition
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>