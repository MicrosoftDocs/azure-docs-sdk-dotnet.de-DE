<Type Name="IndexingParametersExtensions" FullName="Microsoft.Azure.Search.Models.IndexingParametersExtensions">
  <TypeSignature Language="C#" Value="public static class IndexingParametersExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexingParametersExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingParametersExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexingParametersExtensions" />
  <TypeSignature Language="F#" Value="type IndexingParametersExtensions = class" />
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
            Definiert Erweiterungsmethoden für die "indexingparameters"-Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DoNotFailOnUnsupportedContentType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters DoNotFailOnUnsupportedContentType (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters DoNotFailOnUnsupportedContentType(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.DoNotFailOnUnsupportedContentType(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DoNotFailOnUnsupportedContentType (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member DoNotFailOnUnsupportedContentType : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.DoNotFailOnUnsupportedContentType parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <summary>
            Gibt an, dass <c cref="F:Microsoft.Azure.Search.Models.BlobExtractionMode.StorageMetadata">BlobExtractionMode.StorageMetadata</c> Blob Extraktion Modus wird automatisch für Blobs, der nicht unterstützten Inhaltstypen verwendet werden. Der Standardwert ist false.
            </summary>
        <returns />
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeFileNameExtensions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ExcludeFileNameExtensions (this Microsoft.Azure.Search.Models.IndexingParameters parameters, params string[] extensions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ExcludeFileNameExtensions(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string[] extensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ExcludeFileNameExtensions(Microsoft.Azure.Search.Models.IndexingParameters,System.String[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExcludeFileNameExtensions (parameters As IndexingParameters, ParamArray extensions As String()) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ExcludeFileNameExtensions : Microsoft.Azure.Search.Models.IndexingParameters * string[] -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ExcludeFileNameExtensions (parameters, extensions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="extensions" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <param name="extensions">Dateierweiterungen, die von der Indizierung ausschließen.</param>
        <summary>
            Gibt an, dass der Indexer Blobs mit den Dateinamenerweiterungen nicht indizieren, die Sie angeben. Jede Zeichenfolge ist ein Erweiterungen, die mit einem führenden Punkt. Z. B. "PDF", ".docx", usw. Wenn Sie die gleiche Erweiterung an diese Methode und IndexFileNameExtensions übergeben, werden Blobs mit dieser Erweiterung aus der Indizierung ausgeschlossen werden (d. h. für diese Methode hat Vorrang vor).
            Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />.
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexFileNameExtensions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters IndexFileNameExtensions (this Microsoft.Azure.Search.Models.IndexingParameters parameters, params string[] extensions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters IndexFileNameExtensions(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string[] extensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexFileNameExtensions(Microsoft.Azure.Search.Models.IndexingParameters,System.String[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IndexFileNameExtensions (parameters As IndexingParameters, ParamArray extensions As String()) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member IndexFileNameExtensions : Microsoft.Azure.Search.Models.IndexingParameters * string[] -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexFileNameExtensions (parameters, extensions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="extensions" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <param name="extensions">Dateierweiterungen, die in die Indizierung eingeschlossen werden sollen.</param>
        <summary>
            Gibt an, dass der Indexer nur Blobs mit den Dateinamenerweiterungen indiziert wird, die Sie angeben. Jede Zeichenfolge ist ein Erweiterungen, die mit einem führenden Punkt. Z. B. "PDF", ".docx", usw. Wenn Sie die gleiche Erweiterung an diese Methode und ExcludeFileNameExtensions übergeben, werden Blobs mit dieser Erweiterung aus der Indizierung ausgeschlossen werden (d. h. ExcludeFileNameExtensions hat Vorrang vor).
            Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />.
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexStorageMetadataOnly">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters IndexStorageMetadataOnly (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters IndexStorageMetadataOnly(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexStorageMetadataOnly(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IndexStorageMetadataOnly (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member IndexStorageMetadataOnly : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexStorageMetadataOnly parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete. Please use SetBlobExtractionMode(BlobExtractionMode.StorageMetadata).")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <summary> 
            Gibt an, dass der Indexer nur die Metadaten für die Speicherung Index und der Extrahierungsprozess Dokument vollständig zu überspringen. Dies ist hilfreich, wenn Sie weder den Inhalt des Dokuments noch die inhaltstypspezifischen Metadateneigenschaften benötigen. Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />. 
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks> 
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher. 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseDelimitedTextFiles">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ParseDelimitedTextFiles (this Microsoft.Azure.Search.Models.IndexingParameters parameters, params string[] headers);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ParseDelimitedTextFiles(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string[] headers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseDelimitedTextFiles(Microsoft.Azure.Search.Models.IndexingParameters,System.String[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ParseDelimitedTextFiles (parameters As IndexingParameters, ParamArray headers As String()) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ParseDelimitedTextFiles : Microsoft.Azure.Search.Models.IndexingParameters * string[] -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseDelimitedTextFiles (parameters, headers)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="headers" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <param name="headers">
            Gibt die Spaltenüberschriften, die der Indexer verwendet, die Werte bestimmter Felder in der Azure Search-Index zugeordnet. Sie alle Header angeben, geht davon aus der Indexer, die erste nicht leeren Zeile jedes BLOBs durch Kommas getrennte Header enthält.
            </param>
        <summary>
            Weist der Indexer wird davon ausgegangen, dass alle Blobs durch Trennzeichen getrennten Textdateien sind. Derzeit nur durch Trennzeichen getrennte Werten (CSV) Text-Dateien werden unterstützt.
            Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-index-csv-blobs" />.
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseJson">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ParseJson (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ParseJson(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJson(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ParseJson (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ParseJson : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJson parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <summary>
            Weist der Indexer wird davon ausgegangen, dass alle Blobs JSON enthalten, die es anschließend analysiert, dass ein einzelnes Dokument in der Azure Search-Index jedes Blob JSON zugeordnet werden kann.
            Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-index-json-blobs/" />.
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseJsonArrays">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ParseJsonArrays (this Microsoft.Azure.Search.Models.IndexingParameters parameters, string documentRoot = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ParseJsonArrays(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string documentRoot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJsonArrays(Microsoft.Azure.Search.Models.IndexingParameters,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ParseJsonArrays (parameters As IndexingParameters, Optional documentRoot As String = null) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ParseJsonArrays : Microsoft.Azure.Search.Models.IndexingParameters * string -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJsonArrays (parameters, documentRoot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="documentRoot" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <param name="documentRoot">
            Ein optionales JSON-Zeiger, der dem Indexer erläutert, wie das JSON-Array gefunden wird wird, ist dies nicht der obersten Ebene JSON-Eigenschaft der einzelnen BLOBs. Wenn dieser Parameter null oder leer ist, wird der Indexer davon ausgegangen, dass die JSON-Array in der obersten Ebene JSON-Eigenschaft der einzelnen BLOBs gefunden werden kann.
            Der Standardwert lautet null.
            </param>
        <summary>
            Weist der Indexer wird davon ausgegangen, dass alle Blobs JSON-Arrays enthalten, die es anschließend analysiert, dass jedes JSON-Objekt in jedem Array zu einem Dokument in der Azure-Suchindex zugeordnet wird.
            Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-index-json-blobs" />.
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetBlobExtractionMode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters SetBlobExtractionMode (this Microsoft.Azure.Search.Models.IndexingParameters parameters, Microsoft.Azure.Search.Models.BlobExtractionMode extractionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters SetBlobExtractionMode(class Microsoft.Azure.Search.Models.IndexingParameters parameters, class Microsoft.Azure.Search.Models.BlobExtractionMode extractionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.SetBlobExtractionMode(Microsoft.Azure.Search.Models.IndexingParameters,Microsoft.Azure.Search.Models.BlobExtractionMode)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetBlobExtractionMode (parameters As IndexingParameters, extractionMode As BlobExtractionMode) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member SetBlobExtractionMode : Microsoft.Azure.Search.Models.IndexingParameters * Microsoft.Azure.Search.Models.BlobExtractionMode -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.SetBlobExtractionMode (parameters, extractionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="extractionMode" Type="Microsoft.Azure.Search.Models.BlobExtractionMode" />
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <param name="extractionMode">Ein <c cref="T:Microsoft.Azure.Search.Models.BlobExtractionMode">BlobExtractionMode</c> Wert, der angibt, welche zum Indizieren.</param>
        <summary>
            Gibt an, welche Teile eines BLOBs von Blob-Speicher-Indexer indiziert werden. 
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks>
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher.
            <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters SkipContent (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters SkipContent(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.SkipContent(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SkipContent (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member SkipContent : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.SkipContent parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete. Please use SetBlobExtractionMode(BlobExtractionMode.AllMetadata).")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">"Indexingparameters" konfigurieren.</param>
        <summary>
            Gibt an, dass der Indexer Extrahieren von Metadaten, aber die Extraktion von Inhalt für alle Blobs zu überspringen. Wenn Sie Inhalt Extraktion für nur einige Blobs überspringen möchten, fügen Sie AzureSearch_SkipContent-Metadaten für diese Blobs statt dieser Option einzeln. Ausführliche Informationen finden Sie unter <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />. 
            </summary>
        <returns>Der "indexingparameters"-Instanz.</returns>
        <remarks> 
            Diese Option gilt nur für Indexer, Index-Azure-Blob-Speicher. 
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>