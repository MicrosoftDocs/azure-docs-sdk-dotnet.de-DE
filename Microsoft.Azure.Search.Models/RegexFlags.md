<Type Name="RegexFlags" FullName="Microsoft.Azure.Search.Models.RegexFlags">
  <TypeSignature Language="C#" Value="public sealed class RegexFlags : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.RegexFlags&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RegexFlags extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.RegexFlags&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.RegexFlags" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RegexFlags&#xA;Inherits ExtensibleEnum(Of RegexFlags)" />
  <TypeSignature Language="F#" Value="type RegexFlags = class&#xA;    inherit ExtensibleEnum&lt;RegexFlags&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.RegexFlags&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.RegexFlags</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.RegexFlags&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Definiert Flags, die kombiniert werden können, um zu steuern, wie reguläre Ausdrücke im Muster Analyzer und Muster Tokenizer verwendet werden.
            <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#field_summary" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CanonEq">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags CanonEq;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags CanonEq" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.CanonEq" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CanonEq As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable CanonEq : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.CanonEq" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht die kanonische Äquivalenz. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#CANON_EQ" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaseInsensitive">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags CaseInsensitive;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags CaseInsensitive" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.CaseInsensitive" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CaseInsensitive As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable CaseInsensitive : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.CaseInsensitive" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht die Groß-/Kleinschreibung übereinstimmende. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#CASE_INSENSITIVE" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Comments">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags Comments;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags Comments" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.Comments" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Comments As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable Comments : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Comments" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht Leerzeichen und Kommentare im Muster. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#COMMENTS" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.RegexFlags Create (string flagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.RegexFlags Create(string flagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.RegexFlags.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (flagExpression As String) As RegexFlags" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Create flagExpression" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="flagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="flagExpression">
            Name des Regex-Flag oder einen Ausdruck, bestehend aus mindestens zwei Flags, die durch senkrechte Striche (|) getrennt.
            </param>
        <summary>
            Erstellt eine neue Instanz der RegexFlags oder eine vorhandene Instanz zurück, wenn dem angegebenen Namen, die von einer bekannten Regex-Flag übereinstimmt.
            </summary>
        <returns>Eine RegexFlags-Instanz mit dem angegebenen Ausdruck.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DotAll">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags DotAll;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags DotAll" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.DotAll" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DotAll As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable DotAll : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.DotAll" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dotall-Modus aktiviert. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#DOTALL" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Literal">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags Literal;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags Literal" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.Literal" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Literal As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable Literal : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Literal" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht das literal Analysieren des Musters. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#LITERAL" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Multiline">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags Multiline;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags Multiline" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.Multiline" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Multiline As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable Multiline : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Multiline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht Mehrzeilenmodus. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#MULTILINE" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_BitwiseOr">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.RegexFlags operator | (Microsoft.Azure.Search.Models.RegexFlags lhs, Microsoft.Azure.Search.Models.RegexFlags rhs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.RegexFlags op_BitwiseOr(class Microsoft.Azure.Search.Models.RegexFlags lhs, class Microsoft.Azure.Search.Models.RegexFlags rhs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.RegexFlags.op_BitwiseOr(Microsoft.Azure.Search.Models.RegexFlags,Microsoft.Azure.Search.Models.RegexFlags)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator Or (lhs As RegexFlags, rhs As RegexFlags) As RegexFlags" />
      <MemberSignature Language="F#" Value="static member ( ||| ) : Microsoft.Azure.Search.Models.RegexFlags * Microsoft.Azure.Search.Models.RegexFlags -&gt; Microsoft.Azure.Search.Models.RegexFlags" Usage="lhs ||| rhs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lhs" Type="Microsoft.Azure.Search.Models.RegexFlags" />
        <Parameter Name="rhs" Type="Microsoft.Azure.Search.Models.RegexFlags" />
      </Parameters>
      <Docs>
        <param name="lhs">Die linke Seite des OR-Ausdrucks.</param>
        <param name="rhs">Der rechten Seite des OR-Ausdrucks.</param>
        <summary>
            Overloads bitweisen oder Operator kombiniert zwei RegexFlags.
            </summary>
        <returns>
            Eine neue RegexFlags, die das Ergebnis der Verkettung der beiden angegebenen RegexFlags wird getrennt durch einen senkrechten Strich (|).
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.RegexFlags (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.RegexFlags op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.RegexFlags.op_Implicit(System.String)~Microsoft.Azure.Search.Models.RegexFlags" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As RegexFlags" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">zu konvertierende Zeichenfolge.</param>
        <summary>
            Definiert die implizite Konvertierung von Zeichenfolgen in RegexFlags.
            </summary>
        <returns>Die Zeichenfolge als eine RegexFlags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnicodeCase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags UnicodeCase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags UnicodeCase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.UnicodeCase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UnicodeCase As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable UnicodeCase : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.UnicodeCase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht das Unicode-kompatible Groß-/Kleinschreibung Faltung. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#UNICODE_CASE" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnixLines">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags UnixLines;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags UnixLines" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.UnixLines" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UnixLines As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable UnixLines : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.UnixLines" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermöglicht es Unix-Zeilen-Modus. <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#UNIX_LINES" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>