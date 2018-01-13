<Type Name="CompositeTableKey" FullName="Microsoft.Azure.Mobile.Server.CompositeTableKey">
  <TypeSignature Language="C#" Value="public class CompositeTableKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CompositeTableKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />
  <TypeSignature Language="VB.NET" Value="Public Class CompositeTableKey" />
  <TypeSignature Language="F#" Value="type CompositeTableKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> enthält einen oder mehrere Schlüssel verwendet, um eine einzelne Zeile in einer Tabelle zu identifizieren.
            Das Zeichenfolgenformat ein <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> ist eine durch Trennzeichen getrennte Liste (ohne LWS) optional mit einfachen Anführungszeichen Begriffe.
            Die Begriffe ist es in Anführungszeichen gesetzt werden, wenn sie ein Komma enthalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CompositeTableKey (params string[] segments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] segments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray segments As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.CompositeTableKey : string[] -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="new Microsoft.Azure.Mobile.Server.CompositeTableKey segments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="segments" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="segments">Der sortierte Satz von <see cref="T:System.String" /> Pfadsegmenten, aus denen des zusammengesetzten Schlüssels.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> mit einer bestimmten Anzahl von <see cref="T:System.String" /> , die eine geordnete Liste von Segmenten, aus denen des zusammengesetzten Schlüssels darstellt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parse">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.CompositeTableKey Parse (string tableKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.CompositeTableKey Parse(string tableKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.Parse(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Parse (tableKey As String) As CompositeTableKey" />
      <MemberSignature Language="F#" Value="static member Parse : string -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.Parse tableKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.CompositeTableKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableKey">Der Wert des zusammengesetzten Schlüssels enthält.</param>
        <summary>
            Analysiert eine Zeichenfolge als eine <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />. Der Wert muss eine durch Trennzeichen getrennte Liste (ohne LWS) optional mit einfachen Anführungszeichen Begriffe sein.
            Wenn der Wert nicht gültig ist ein <see cref="T:System.ArgumentException" /> ausgelöst wird.
            </summary>
        <returns>Eine neue <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />-Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Segments">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; Segments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; Segments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.CompositeTableKey.Segments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Segments As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Segments : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.Segments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die geordnete <see cref="T:System.Collections.ObjectModel.Collection`1" /> der Segmente, aus denen des zusammengesetzten Schlüssels.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="compositeTableKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Generiert eine <see cref="T:System.String" /> Darstellung des zusammengesetzten Schlüssels.
            </summary>
        <returns>Ein <see cref="T:System.String" /> Darstellung des zusammengesetzten Schlüssels.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string tableKey, out Microsoft.Azure.Mobile.Server.CompositeTableKey compositeTableKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string tableKey, [out] class Microsoft.Azure.Mobile.Server.CompositeTableKey&amp; compositeTableKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.TryParse(System.String,Microsoft.Azure.Mobile.Server.CompositeTableKey@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (tableKey As String, ByRef compositeTableKey As CompositeTableKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.TryParse (tableKey, compositeTableKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableKey" Type="System.String" />
        <Parameter Name="compositeTableKey" Type="Microsoft.Azure.Mobile.Server.CompositeTableKey&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="tableKey">Der Wert des zusammengesetzten Schlüssels enthält.</param>
        <param name="compositeTableKey">Wenn die-Methode zurückgibt <c>"true"</c> dann <paramref name="compositeTableKey" /> enthält das Ergebnis ist andernfalls <c>null</c>.</param>
        <summary>
            Versuche, die beim Erstellen eines neuen <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> aus einem angegebenen <paramref name="tableKey" />.
            Der Rückgabewert gibt an, ob die Analyse erfolgreich war.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>