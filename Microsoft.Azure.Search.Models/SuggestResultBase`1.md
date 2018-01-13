<Type Name="SuggestResultBase&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.SuggestResultBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class SuggestResultBase&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SuggestResultBase`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SuggestResultBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SuggestResultBase(Of T)" />
  <TypeSignature Language="F#" Value="type SuggestResultBase&lt;'T (requires 'T : null)&gt; = class" />
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
            Abstrakte Basisklasse für ein Ergebnis mit einem Dokument gefunden, die von einer vorschlagsabfrage sowie die zugehörigen Metadaten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SuggestResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestResultBase`1.#ctor" />
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
            Initialisiert eine neue Instanz der "suggestresultbase"-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public T Document { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestResultBase`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public Property Document As T" />
      <MemberSignature Language="F#" Value="member this.Document : 'T with get, set" Usage="Microsoft.Azure.Search.Models.SuggestResultBase&lt;'T (requires 'T : null)&gt;.Document" />
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
            Ruft das Dokument auf dem der vorgeschlagene Text basiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestResultBase`1.Text" />
      <MemberSignature Language="VB.NET" Value="Public Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestResultBase&lt;'T (requires 'T : null)&gt;.Text" />
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
            Ruft den Text des vorschlagsergebnisses ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>