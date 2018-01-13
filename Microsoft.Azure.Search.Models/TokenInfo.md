<Type Name="TokenInfo" FullName="Microsoft.Azure.Search.Models.TokenInfo">
  <TypeSignature Language="C#" Value="public class TokenInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TokenInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TokenInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenInfo" />
  <TypeSignature Language="F#" Value="type TokenInfo = class" />
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
            Informationen zu einem zurückgegebene Token über einen Analyzer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TokenInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInfo (string token = null, Nullable&lt;int&gt; startOffset = null, Nullable&lt;int&gt; endOffset = null, Nullable&lt;int&gt; position = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string token, valuetype System.Nullable`1&lt;int32&gt; startOffset, valuetype System.Nullable`1&lt;int32&gt; endOffset, valuetype System.Nullable`1&lt;int32&gt; position) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenInfo.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional token As String = null, Optional startOffset As Nullable(Of Integer) = null, Optional endOffset As Nullable(Of Integer) = null, Optional position As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.TokenInfo : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.TokenInfo" Usage="new Microsoft.Azure.Search.Models.TokenInfo (token, startOffset, endOffset, position)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="startOffset" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="endOffset" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="position" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="token">Das zurückgegebene Token über die Analyzer.</param>
        <param name="startOffset">Der Index des ersten Zeichens des Tokens im Eingabetext an.</param>
        <param name="endOffset">Der Index des letzten Zeichens des Tokens im Eingabetext an.</param>
        <param name="position">Die Position des Tokens im Eingabetext relativ zu anderen Token. Das erste Token in der Eingabetext hat Position 0, der nächsten Position 1 und So weiter. Je nach den Analyzer, die verwendet wird möglicherweise einige Token derselben Position, z. B. Wenn sie die Synonyme zueinander sind.</param>
        <summary>
            Initialisiert eine neue Instanz der TokenInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EndOffset { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EndOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.EndOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property EndOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EndOffset : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.EndOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Index des letzten Zeichens des Tokens im Eingabetext an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Position { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.Position" />
      <MemberSignature Language="VB.NET" Value="Public Property Position As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Position : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.Position" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="position")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Position des Tokens im Eingabetext relativ zu anderen Token ab. Das erste Token in der Eingabetext hat Position 0, der nächsten Position 1 und So weiter. Je nach den Analyzer, die verwendet wird möglicherweise einige Token derselben Position, z. B. Wenn sie die Synonyme zueinander sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StartOffset { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property StartOffset As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StartOffset : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Index des ersten Zeichens des Tokens im Eingabetext an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TokenInfo.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Search.Models.TokenInfo.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das zurückgegebene Token über die Analyzer ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>