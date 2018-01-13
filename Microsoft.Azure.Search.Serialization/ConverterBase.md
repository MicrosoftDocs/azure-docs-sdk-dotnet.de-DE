<Type Name="ConverterBase" FullName="Microsoft.Azure.Search.Serialization.ConverterBase">
  <TypeSignature Language="C#" Value="public abstract class ConverterBase : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConverterBase extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ConverterBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConverterBase&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type ConverterBase = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Basisklasse für benutzerdefinierte JsonConverters.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ConverterBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Advance">
      <MemberSignature Language="C#" Value="protected void Advance (Newtonsoft.Json.JsonReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Advance(class Newtonsoft.Json.JsonReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Advance(Newtonsoft.Json.JsonReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Advance (reader As JsonReader)" />
      <MemberSignature Language="F#" Value="member this.Advance : Newtonsoft.Json.JsonReader -&gt; unit" Usage="converterBase.Advance reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
      </Parameters>
      <Docs>
        <param name="reader">Zum Fortsetzen der JSON-Reader.</param>
        <summary>
            Verschiebt den angegebenen JSON-Reader oder löst eine JsonSerializationException aus, wenn es kann nicht gesetzt werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect">
      <MemberSignature Language="C#" Value="protected void Expect (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Expect(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Expect (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader">Der JSON-Reader.</param>
        <param name="expectedToken">Das JSON-Token, das auf dem der Reader positioniert werden soll.</param>
        <param name="expectedValue">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</param>
        <summary>
            Bestätigt, dass das angegebene JSON-Reader mit dem erwarteten Typ auf ein Token positioniert ist. Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht. Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expect&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue Expect&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue Expect&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.Expect``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function Expect(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.Expect : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.Expect (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue">Der erwartete Typ des Werts des aktuellen JSON-Tokens.</typeparam>
        <param name="reader">Der JSON-Reader.</param>
        <param name="expectedToken">Das JSON-Token, das auf dem der Reader positioniert werden soll.</param>
        <param name="expectedValue">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</param>
        <summary>
            Bestätigt, dass die angegebene JSON-Reader sich auf ein Token mit dem erwarteten Typ befindet und den Wert des Tokens Ruft, sofern vorhanden. Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht. Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an.
            </summary>
        <returns>
            Der Wert des aktuellen JSON-webtoken oder default(TValue), wenn das aktuelle Token keinen Wert verfügt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance">
      <MemberSignature Language="C#" Value="protected void ExpectAndAdvance (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ExpectAndAdvance(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ExpectAndAdvance (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null)" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; unit" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="reader">Der JSON-Reader.</param>
        <param name="expectedToken">Das JSON-Token, das auf dem der Reader positioniert werden soll.</param>
        <param name="expectedValue">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</param>
        <summary>
            Bestätigt, dass das angegebene JSON-Reader mit dem erwarteten Typ auf ein Token positioniert ist. Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht. Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an. Andernfalls versucht diese Methode, die JSON-Reader zum nächsten Position zu gelangen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpectAndAdvance&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="protected TValue ExpectAndAdvance&lt;TValue&gt; (Newtonsoft.Json.JsonReader reader, Newtonsoft.Json.JsonToken expectedToken, object expectedValue = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !!TValue ExpectAndAdvance&lt;TValue&gt;(class Newtonsoft.Json.JsonReader reader, valuetype Newtonsoft.Json.JsonToken expectedToken, object expectedValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Serialization.ConverterBase.ExpectAndAdvance``1(Newtonsoft.Json.JsonReader,Newtonsoft.Json.JsonToken,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function ExpectAndAdvance(Of TValue) (reader As JsonReader, expectedToken As JsonToken, Optional expectedValue As Object = null) As TValue" />
      <MemberSignature Language="F#" Value="member this.ExpectAndAdvance : Newtonsoft.Json.JsonReader * Newtonsoft.Json.JsonToken * obj -&gt; 'Value" Usage="converterBase.ExpectAndAdvance (reader, expectedToken, expectedValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="expectedToken" Type="Newtonsoft.Json.JsonToken" />
        <Parameter Name="expectedValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TValue">Der erwartete Typ des Werts des aktuellen JSON-Tokens.</typeparam>
        <param name="reader">Der JSON-Reader.</param>
        <param name="expectedToken">Das JSON-Token, das auf dem der Reader positioniert werden soll.</param>
        <param name="expectedValue">Dies ist optional; Der erwartete Wert des aktuellen Tokens JSON.</param>
        <summary>
            Bestätigt, dass die angegebene JSON-Reader sich auf ein Token mit dem erwarteten Typ befindet und den Wert des Tokens Ruft, sofern vorhanden. Optional bestätigt, dass der Wert des Tokens mit einen angegebenen erwarteten Wert entspricht. Wenn einer der Assertionen fehlschlägt, löst diese Methode eine JsonSerializationException an. Andernfalls versucht diese Methode, die JSON-Reader zum nächsten Position zu gelangen.
            </summary>
        <returns>
            Der Wert der JSON-webtoken vor dem Vorlauf der Leser oder default(TValue), wenn das Token über keinen Wert verfügt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>