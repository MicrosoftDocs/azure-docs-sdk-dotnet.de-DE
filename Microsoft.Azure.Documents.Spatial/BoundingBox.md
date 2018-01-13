<Type Name="BoundingBox" FullName="Microsoft.Azure.Documents.Spatial.BoundingBox">
  <TypeSignature Language="C#" Value="public sealed class BoundingBox : IEquatable&lt;Microsoft.Azure.Documents.Spatial.BoundingBox&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BoundingBox extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.BoundingBox&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BoundingBox&#xA;Implements IEquatable(Of BoundingBox)" />
  <TypeSignature Language="F#" Value="type BoundingBox = class&#xA;    interface IEquatable&lt;BoundingBox&gt;" />
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
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.BoundingBox&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.BoundingBoxJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt einen-Koordinate Bereich für Geometrien im Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BoundingBox (Microsoft.Azure.Documents.Spatial.Position min, Microsoft.Azure.Documents.Spatial.Position max);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Spatial.Position min, class Microsoft.Azure.Documents.Spatial.Position max) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.#ctor(Microsoft.Azure.Documents.Spatial.Position,Microsoft.Azure.Documents.Spatial.Position)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (min As Position, max As Position)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.BoundingBox : Microsoft.Azure.Documents.Spatial.Position * Microsoft.Azure.Documents.Spatial.Position -&gt; Microsoft.Azure.Documents.Spatial.BoundingBox" Usage="new Microsoft.Azure.Documents.Spatial.BoundingBox (min, max)" />
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
        <Parameter Name="min" Type="Microsoft.Azure.Documents.Spatial.Position" />
        <Parameter Name="max" Type="Microsoft.Azure.Documents.Spatial.Position" />
      </Parameters>
      <Docs>
        <param name="min">
            Niedrigste Werte für alle Achsen des umgebenden Felds.
            </param>
        <param name="max">
            Höchste Werte für alle Achsen des umgebenden Felds.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.BoundingBox other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.BoundingBox other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.Equals(Microsoft.Azure.Documents.Spatial.BoundingBox)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As BoundingBox) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.BoundingBox -&gt; bool" Usage="boundingBox.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.BoundingBox" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />Dieser Begrenzungsrahmen verglichen werden soll.</param>
        <summary>
            Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> ist gleich der <paramref name="other" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
          <c>"true"</c> Wenn umgebende Felder gleich sind. <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="boundingBox.Equals obj" />
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
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. </param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            "true", wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist; andernfalls "false".
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.BoundingBox.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="boundingBox.GetHashCode " />
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
            Dient als Hashfunktion für <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" /> Typ im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein Hashcode für die aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.BoundingBox" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Position Max { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Position Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.BoundingBox.Max" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Max As Position" />
      <MemberSignature Language="F#" Value="member this.Max : Microsoft.Azure.Documents.Spatial.Position" Usage="Microsoft.Azure.Documents.Spatial.BoundingBox.Max" />
      <MemberType>Property</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Position</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den höchsten Werten für alle Achsen des umgebenden Felds im Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Höchste Werte für alle Achsen des umgebenden Felds.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Position Min { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Position Min" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.BoundingBox.Min" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Min As Position" />
      <MemberSignature Language="F#" Value="member this.Min : Microsoft.Azure.Documents.Spatial.Position" Usage="Microsoft.Azure.Documents.Spatial.BoundingBox.Min" />
      <MemberType>Property</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Position</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den niedrigsten Werten für alle Achsen des umgebenden Felds im Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Niedrigste Werte für alle Achsen des umgebenden Felds.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>