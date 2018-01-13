<Type Name="Range&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class Range&lt;TKey&gt; : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Range`1&lt;TKey&gt; extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Range(Of TKey)&#xA;Implements IEquatable(Of Range(Of TKey))" />
  <TypeSignature Language="F#" Value="type Range&lt;'Key&gt; = class&#xA;    interface IEquatable&lt;Range&lt;'Key&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TKey">Typ der Werte.</typeparam>
    <summary>Repräsentiert eine inklusiv links, rechts ausschließliche Anzahl von Werten des Typs t</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Range (TKey low);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!TKey low) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (low As TKey)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; : 'Key -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt;" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; low" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="low" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="low">Niedrige Begrenzungswert (inklusiv).</param>
        <summary>
            Erstellt basierend auf seiner niedrig Begrenzungswert Bereich an. Der niedrige Grenzwert festgelegt ist, auf die <paramref name="low" /> während der hohe Grenzwert auf maximal möglichen Wert, d. h. festgelegt ist plus unendlich.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Range (TKey low, TKey high);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!TKey low, !TKey high) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.#ctor(`0,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (low As TKey, high As TKey)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; : 'Key * 'Key -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt;" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; (low, high)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="low" Type="TKey" />
        <Parameter Name="high" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="low">Niedrige Begrenzungswert (inklusiv).</param>
        <param name="high">Hohe Begrenzungswert (exklusiv).</param>
        <summary>
            Erstellt basierend auf der niedrigen und hohen Begrenzungswerte Bereich an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Range(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; -&gt; bool" Usage="range.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="other">Bereich für den Vergleich mit.</param>
        <summary>
            Führt Vergleiche auf Gleichheit mit einem anderen Bereich an.
            </summary>
        <returns>True, wenn der gleiche Bereich andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="range.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</param>
        <summary>
            Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.
            </summary>
        <returns>True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="range.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Berechnet den Hashcode für diese Instanz an.
            </summary>
        <returns>Der Hashcode für das Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public TKey High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey High" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As TKey" />
      <MemberSignature Language="F#" Value="member this.High : 'Key" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt;.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den hohen Grenzwert (exklusiv).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighIsMax">
      <MemberSignature Language="C#" Value="public bool HighIsMax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HighIsMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.HighIsMax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HighIsMax As Boolean" />
      <MemberSignature Language="F#" Value="member this.HighIsMax : bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt;.HighIsMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            True, wenn die hohe Grenze ist gleich + unendlich Wert. andernfalls "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public TKey Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey Low" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As TKey" />
      <MemberSignature Language="F#" Value="member this.Low : 'Key" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt;.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den niedrigen Begrenzungswert (inklusiv).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="range.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Konvertiert das Objekt in seine Zeichenfolgendarstellung.
            </summary>
        <returns>Entspricht der Zeichenfolgendarstellung des Objekts.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>