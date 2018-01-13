<Type Name="EntityPropertyConverter" FullName="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter">
  <TypeSignature Language="C#" Value="public static class EntityPropertyConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EntityPropertyConverter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter" />
  <TypeSignature Language="VB.NET" Value="Public Class EntityPropertyConverter" />
  <TypeSignature Language="F#" Value="type EntityPropertyConverter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            EntityPropertyConverter-Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConvertBack&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T ConvertBack&lt;T&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T ConvertBack&lt;T&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'T" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack (flattenedEntityProperties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="flattenedEntityProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts zum Auffüllen</typeparam>
        <param name="flattenedEntityProperties">Das Eigenschaftenwörterbuch vereinfachten Entität.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Vollständige Objektdiagramm vom Typ T mit der vereinfachten Entität Eigenschaftenwörterbuch rekonstruiert und dominant zurück.
            Das Eigenschaftenwörterbuch kann nur grundlegende Eigenschaften, nur geschachtelte Eigenschaften oder eine Kombination beider Typen enthalten.
            </summary>
        <returns>Das Ergebnis mit dem dominant Objekt mit der vollständigen Objekthierarchie.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T ConvertBack&lt;T&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T ConvertBack&lt;T&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'T" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack (flattenedEntityProperties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="flattenedEntityProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">Der Typ des Objekts zum Auffüllen</typeparam>
        <param name="flattenedEntityProperties">Das Eigenschaftenwörterbuch vereinfachten Entität.</param>
        <param name="entityPropertyConverterOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Vollständige Objektdiagramm vom Typ T mit der vereinfachten Entität Eigenschaftenwörterbuch rekonstruiert und dominant zurück.
            Das Eigenschaftenwörterbuch kann nur grundlegende Eigenschaften, nur geschachtelte Eigenschaften oder eine Kombination beider Typen enthalten.
            </summary>
        <returns>Das Ergebnis mit dem dominant Objekt mit der vollständigen Objekthierarchie.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPropertyNameDelimiter">
      <MemberSignature Language="C#" Value="public const string DefaultPropertyNameDelimiter;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultPropertyNameDelimiter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.DefaultPropertyNameDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultPropertyNameDelimiter As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultPropertyNameDelimiter : string" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.DefaultPropertyNameDelimiter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Trennzeichen des Eigenschaft.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object root, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.Dictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object root, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten(System.Object,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.Dictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten (root, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="root" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="root">Das Objekt zum vereinfachen und zu konvertieren.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Objektdiagramm durchläuft, fasst zusammen und aller verschachtelte (und nicht geschachtelte) Eigenschaften zu EntityProperties konvertiert, speichert diese im Eigenschaftenwörterbuch.
            Die Schlüssel werden erstellt, durch die Namen der Eigenschaften, die während der ersten Durchlauf vor Reihenfolge Tiefe vom Stamm auf jede End-Knoten-Eigenschaft, die durch "_" getrennten besucht anfügen.
            Können komplexe Objekte in Systemen mit permanenten Speicher gespeichert oder zwischen Webdienste in eine generische Methode übergeben werden.
            </summary>
        <returns>Das Ergebnis mit <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des Stammobjekts vereinfachten.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object root, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.Dictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object root, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten(System.Object,Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.Dictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten (root, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="root" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="root">Das Objekt zum vereinfachen und zu konvertieren.</param>
        <param name="entityPropertyConverterOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Objektdiagramm durchläuft, fasst zusammen und aller verschachtelte (und nicht geschachtelte) Eigenschaften zu EntityProperties konvertiert, speichert diese im Eigenschaftenwörterbuch.
            Die Schlüssel werden erstellt, durch die Namen der Eigenschaften, die während der ersten Durchlauf vor Reihenfolge Tiefe vom Stamm auf jede End-Knoten-Eigenschaft, die durch "_" getrennten besucht anfügen.
            Können komplexe Objekte in Systemen mit permanenten Speicher gespeichert oder zwischen Webdienste in eine generische Methode übergeben werden.
            </summary>
        <returns>Das Ergebnis mit <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des Stammobjekts vereinfachten.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>