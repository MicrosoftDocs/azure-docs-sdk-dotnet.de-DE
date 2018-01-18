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
            <span data-ttu-id="6de99-101">EntityPropertyConverter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6de99-101">EntityPropertyConverter class.</span></span>
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
        <typeparam name="T"><span data-ttu-id="6de99-102">Der Typ des Objekts zum Auffüllen</span><span class="sxs-lookup"><span data-stu-id="6de99-102">The type of the object to populate</span></span></typeparam>
        <param name="flattenedEntityProperties"><span data-ttu-id="6de99-103">Das Eigenschaftenwörterbuch vereinfachten Entität.</span><span class="sxs-lookup"><span data-stu-id="6de99-103">The flattened entity property dictionary.</span></span></param>
        <param name="operationContext"><span data-ttu-id="6de99-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6de99-104">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="6de99-105">Vollständige Objektdiagramm vom Typ T mit der vereinfachten Entität Eigenschaftenwörterbuch rekonstruiert und dominant zurück.</span><span class="sxs-lookup"><span data-stu-id="6de99-105">Reconstructs the complete object graph of type T using the flattened entity property dictionary and returns reconstructed object.</span></span>
            <span data-ttu-id="6de99-106">Das Eigenschaftenwörterbuch kann nur grundlegende Eigenschaften, nur geschachtelte Eigenschaften oder eine Kombination beider Typen enthalten.</span><span class="sxs-lookup"><span data-stu-id="6de99-106">The property dictionary may contain only basic properties, only nested properties or a mix of both types.</span></span>
            </summary>
        <returns><span data-ttu-id="6de99-107">Das Ergebnis mit dem dominant Objekt mit der vollständigen Objekthierarchie.</span><span class="sxs-lookup"><span data-stu-id="6de99-107">The result containing the reconstructed object with its full object hierarchy.</span></span></returns>
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
        <typeparam name="T"><span data-ttu-id="6de99-108">Der Typ des Objekts zum Auffüllen</span><span class="sxs-lookup"><span data-stu-id="6de99-108">The type of the object to populate</span></span></typeparam>
        <param name="flattenedEntityProperties"><span data-ttu-id="6de99-109">Das Eigenschaftenwörterbuch vereinfachten Entität.</span><span class="sxs-lookup"><span data-stu-id="6de99-109">The flattened entity property dictionary.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="6de99-110">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</span><span class="sxs-lookup"><span data-stu-id="6de99-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="6de99-111">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6de99-111">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="6de99-112">Vollständige Objektdiagramm vom Typ T mit der vereinfachten Entität Eigenschaftenwörterbuch rekonstruiert und dominant zurück.</span><span class="sxs-lookup"><span data-stu-id="6de99-112">Reconstructs the complete object graph of type T using the flattened entity property dictionary and returns reconstructed object.</span></span>
            <span data-ttu-id="6de99-113">Das Eigenschaftenwörterbuch kann nur grundlegende Eigenschaften, nur geschachtelte Eigenschaften oder eine Kombination beider Typen enthalten.</span><span class="sxs-lookup"><span data-stu-id="6de99-113">The property dictionary may contain only basic properties, only nested properties or a mix of both types.</span></span>
            </summary>
        <returns><span data-ttu-id="6de99-114">Das Ergebnis mit dem dominant Objekt mit der vollständigen Objekthierarchie.</span><span class="sxs-lookup"><span data-stu-id="6de99-114">The result containing the reconstructed object with its full object hierarchy.</span></span></returns>
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
            <span data-ttu-id="6de99-115">Das Trennzeichen des Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="6de99-115">The property delimiter.</span></span>
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
        <param name="root"><span data-ttu-id="6de99-116">Das Objekt zum vereinfachen und zu konvertieren.</span><span class="sxs-lookup"><span data-stu-id="6de99-116">The object to flatten and convert.</span></span></param>
        <param name="operationContext"><span data-ttu-id="6de99-117">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6de99-117">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="6de99-118">Objektdiagramm durchläuft, fasst zusammen und aller verschachtelte (und nicht geschachtelte) Eigenschaften zu EntityProperties konvertiert, speichert diese im Eigenschaftenwörterbuch.</span><span class="sxs-lookup"><span data-stu-id="6de99-118">Traverses object graph, flattens and converts all nested (and not nested) properties to EntityProperties, stores them in the property dictionary.</span></span>
            <span data-ttu-id="6de99-119">Die Schlüssel werden erstellt, durch die Namen der Eigenschaften, die während der ersten Durchlauf vor Reihenfolge Tiefe vom Stamm auf jede End-Knoten-Eigenschaft, die durch "_" getrennten besucht anfügen.</span><span class="sxs-lookup"><span data-stu-id="6de99-119">The keys are constructed by appending the names of the properties visited during pre-order depth first traversal from root to each end node property delimited by '_'.</span></span>
            <span data-ttu-id="6de99-120">Können komplexe Objekte in Systemen mit permanenten Speicher gespeichert oder zwischen Webdienste in eine generische Methode übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="6de99-120">Allows complex objects to be stored in persistent storage systems or passed between web services in a generic way.</span></span>
            </summary>
        <returns><span data-ttu-id="6de99-121">Das Ergebnis mit <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des Stammobjekts vereinfachten.</span><span class="sxs-lookup"><span data-stu-id="6de99-121">The result containing <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> objects for all properties of the flattened root object.</span></span></returns>
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
        <param name="root"><span data-ttu-id="6de99-122">Das Objekt zum vereinfachen und zu konvertieren.</span><span class="sxs-lookup"><span data-stu-id="6de99-122">The object to flatten and convert.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="6de99-123">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</span><span class="sxs-lookup"><span data-stu-id="6de99-123">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="6de99-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6de99-124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="6de99-125">Objektdiagramm durchläuft, fasst zusammen und aller verschachtelte (und nicht geschachtelte) Eigenschaften zu EntityProperties konvertiert, speichert diese im Eigenschaftenwörterbuch.</span><span class="sxs-lookup"><span data-stu-id="6de99-125">Traverses object graph, flattens and converts all nested (and not nested) properties to EntityProperties, stores them in the property dictionary.</span></span>
            <span data-ttu-id="6de99-126">Die Schlüssel werden erstellt, durch die Namen der Eigenschaften, die während der ersten Durchlauf vor Reihenfolge Tiefe vom Stamm auf jede End-Knoten-Eigenschaft, die durch "_" getrennten besucht anfügen.</span><span class="sxs-lookup"><span data-stu-id="6de99-126">The keys are constructed by appending the names of the properties visited during pre-order depth first traversal from root to each end node property delimited by '_'.</span></span>
            <span data-ttu-id="6de99-127">Können komplexe Objekte in Systemen mit permanenten Speicher gespeichert oder zwischen Webdienste in eine generische Methode übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="6de99-127">Allows complex objects to be stored in persistent storage systems or passed between web services in a generic way.</span></span>
            </summary>
        <returns><span data-ttu-id="6de99-128">Das Ergebnis mit <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des Stammobjekts vereinfachten.</span><span class="sxs-lookup"><span data-stu-id="6de99-128">The result containing <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> objects for all properties of the flattened root object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>