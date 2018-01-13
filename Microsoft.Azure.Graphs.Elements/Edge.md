<Type Name="Edge" FullName="Microsoft.Azure.Graphs.Elements.Edge">
  <TypeSignature Language="C#" Value="public class Edge" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Edge extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.Edge" />
  <TypeSignature Language="VB.NET" Value="Public Class Edge" />
  <TypeSignature Language="F#" Value="type Edge = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.EdgeConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der Speichercontainer für Edge-Daten.
            Unterstützt die Deserialisierung von GraphSON-Format.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Edge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Graphs.Elements.Edge" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.GetProperties" />
      <MemberSignature Language="VB.NET" Value="Public Iterator Function GetProperties () As IEnumerable(Of Property)" />
      <MemberSignature Language="F#" Value="member this.GetProperties : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.Property&gt;" Usage="edge.GetProperties " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.IteratorStateMachine(typeof(Microsoft.Azure.Graphs.Elements.Edge/&lt;GetProperties&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft alle Eigenschaften auf den Rand an.
            </summary>
        <returns>Aufzählbare Eigenschaften Kanten.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.Elements.Property GetProperty (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.Elements.Property GetProperty(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.GetProperty(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProperty (key As String) As Property" />
      <MemberSignature Language="F#" Value="member this.GetProperty : string -&gt; Microsoft.Azure.Graphs.Elements.Property" Usage="edge.GetProperty key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.Elements.Property</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel der Eigenschaft.</param>
        <summary>
            Ruft eine Eigenschaft auf den Rand, den Schlüssel erhält.
            </summary>
        <returns>Eigenschaft, die Übereinstimmungen zu <paramref name="key" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public object Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Object" />
      <MemberSignature Language="F#" Value="member this.Id : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest.
            </summary>
        <value>
            Der Bezeichner.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InVertexId">
      <MemberSignature Language="C#" Value="public object InVertexId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object InVertexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.InVertexId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InVertexId As Object" />
      <MemberSignature Language="F#" Value="member this.InVertexId : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.InVertexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest in Vertex Bezeichner.
            </summary>
        <value>
            Die Vertex-Bezeichner.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InVertexLabel">
      <MemberSignature Language="C#" Value="public string InVertexLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InVertexLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.InVertexLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InVertexLabel As String" />
      <MemberSignature Language="F#" Value="member this.InVertexLabel : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.InVertexLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest in Vertex Bezeichnung.
            </summary>
        <value>
            Die Vertex-Bezeichnung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.Label" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Bezeichnung fest.
            </summary>
        <value>
            Die Bezeichnung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutVertexId">
      <MemberSignature Language="C#" Value="public object OutVertexId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OutVertexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.OutVertexId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutVertexId As Object" />
      <MemberSignature Language="F#" Value="member this.OutVertexId : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.OutVertexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Out Vertex-Bezeichner.
            </summary>
        <value>
            Die out-Vertex-Bezeichner.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutVertexLabel">
      <MemberSignature Language="C#" Value="public string OutVertexLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutVertexLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.OutVertexLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutVertexLabel As String" />
      <MemberSignature Language="F#" Value="member this.OutVertexLabel : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.OutVertexLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Out Vertex-Bezeichnung.
            </summary>
        <value>
            Die Out Vertex-Bezeichnung.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="edge.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Diese Instanz wird überprüft.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Edge muss eine gültige ID oder Edge muss eine gültige Bezeichnung aufweisen.
            </exception>
        <exception cref="T:System.ArgumentException">
            Edge muss InVertexId angegeben werden.
            oder Edge muss OutVertexId angeben.
            oder Edge muss InVertexLabel angeben.
            oder Edge muss OutVertexLabel angeben.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>