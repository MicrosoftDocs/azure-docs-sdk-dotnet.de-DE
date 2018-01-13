<Type Name="SearchResultBase&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.SearchResultBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class SearchResultBase&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SearchResultBase`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SearchResultBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SearchResultBase(Of T)" />
  <TypeSignature Language="F#" Value="type SearchResultBase&lt;'T (requires 'T : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            Die CLR-Typ, der dem IndexSchema zugeordnet. Instanzen dieses Typs können als Dokumente im Index gespeichert werden.
            </typeparam>
    <summary>
            Abstrakte Basisklasse für ein Ergebnis mit einem Dokument gefunden, die von einer Suchabfrage sowie die zugehörigen Metadaten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SearchResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchResultBase`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der "searchresultbase"-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public T Document { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchResultBase`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public Property Document As T" />
      <MemberSignature Language="F#" Value="member this.Document : 'T with get, set" Usage="Microsoft.Azure.Search.Models.SearchResultBase&lt;'T (requires 'T : null)&gt;.Document" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das von der Suchabfrage gefundene Dokument ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Highlights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.HitHighlights Highlights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.HitHighlights Highlights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchResultBase`1.Highlights" />
      <MemberSignature Language="VB.NET" Value="Public Property Highlights As HitHighlights" />
      <MemberSignature Language="F#" Value="member this.Highlights : Microsoft.Azure.Search.Models.HitHighlights with get, set" Usage="Microsoft.Azure.Search.Models.SearchResultBase&lt;'T (requires 'T : null)&gt;.Highlights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.HitHighlights</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Textausschnitte aus dem Dokument, die die übereinstimmendem Suchbegriffe angeben. NULL, wenn die Treffermarkierung für die Abfrage wurde nicht aktiviert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Score">
      <MemberSignature Language="C#" Value="public double Score { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Score" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchResultBase`1.Score" />
      <MemberSignature Language="VB.NET" Value="Public Property Score As Double" />
      <MemberSignature Language="F#" Value="member this.Score : double with get, set" Usage="Microsoft.Azure.Search.Models.SearchResultBase&lt;'T (requires 'T : null)&gt;.Score" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die relevanzbewertung des Dokuments im Vergleich zu anderen Dokumenten, die von der Abfrage zurückgegebenen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>