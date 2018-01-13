<Type Name="ScoringParameter" FullName="Microsoft.Azure.Search.Models.ScoringParameter">
  <TypeSignature Language="C#" Value="public class ScoringParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScoringParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ScoringParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class ScoringParameter" />
  <TypeSignature Language="F#" Value="type ScoringParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Parameterwert zur Bewertung von Funktionen (z. B. ReferencePointParameter) verwendet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringParameter (string name, Microsoft.Spatial.GeographyPoint value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Spatial.GeographyPoint value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringParameter.#ctor(System.String,Microsoft.Spatial.GeographyPoint)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As GeographyPoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ScoringParameter : string * Microsoft.Spatial.GeographyPoint -&gt; Microsoft.Azure.Search.Models.ScoringParameter" Usage="new Microsoft.Azure.Search.Models.ScoringParameter (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="Microsoft.Spatial.GeographyPoint" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des bewertungs-Parameters.</param>
        <param name="value">Der Wert des bewertungs-Parameters.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "scoringparameter" mit dem angegebenen Namen und GeographyPoint-Wert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringParameter (string name, System.Collections.Generic.IEnumerable&lt;string&gt; values);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IEnumerable`1&lt;string&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringParameter.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, values As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ScoringParameter : string * seq&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.ScoringParameter" Usage="new Microsoft.Azure.Search.Models.ScoringParameter (name, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des bewertungs-Parameters.</param>
        <param name="values">Die Werte des bewertungs-Parameters.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "scoringparameter" mit dem angegebenen Namen und die Zeichenfolgenwerte.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringParameter.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Search.Models.ScoringParameter.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des bewertungs-Parameters.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringParameter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="scoringParameter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt den bewerteten Parameter in einem Format, das in eine Search-API-Anforderung verwendet werden kann.
            </summary>
        <returns>
            Den bewerteten Parameter als einen Doppelpunkt getrennte Name-Wert-Paar (z. B. meinStandort:-122.2,44.8)
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringParameter.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.Values : seq&lt;string&gt;" Usage="Microsoft.Azure.Search.Models.ScoringParameter.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Werte des bewerteten Parameters ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>