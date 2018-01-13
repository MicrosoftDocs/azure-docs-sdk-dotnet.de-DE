<Type Name="AccessCondition" FullName="Microsoft.WindowsAzure.Storage.AccessCondition">
  <TypeSignature Language="C#" Value="public sealed class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
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
            Stellt einen Satz von zugriffsbedingungen für Vorgänge mit den Speicherdiensten verwendet werden soll. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AccessCondition Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.AccessCondition Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="accessCondition.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Geben Sie eine flache Kopie des aktuellen zugriffsbedingung
            </summary>
        <returns>Eine flache Kopie der <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateEmptyCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateEmptyCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateEmptyCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateEmptyCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateEmptyCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateEmptyCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateEmptyCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine leere zugriffsbedingung.
            </summary>
        <returns>Ein leeres <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfAppendPositionEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfAppendPositionEqualCondition (long appendPosition);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfAppendPositionEqualCondition(int64 appendPosition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfAppendPositionEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfAppendPositionEqualCondition (appendPosition As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfAppendPositionEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfAppendPositionEqualCondition appendPosition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appendPosition" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="appendPosition">Eine ganze Zahl, der den Offset angibt und mit der aktuellen Endposition des BLOBs verglichen werden soll.</param>
        <summary>
            Erstellt eine zugriffsbedingung, z. B., dass ein Vorgang ausgeführt wird, nur, wenn die Endposition des Anhang-BLOBs gleich dem angegebenen Wert ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das den Offset, verglichen werden soll.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfExistsCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das eine Bedingung darstellt, in dem eine Ressource vorhanden ist.</returns>
        <remarks>Festlegen von dieser Bedingung für den Zugriff ändert die Anforderung der HTTP einschließen <i>If-Match</i> bedingten Header an.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMatchCondition (string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMatchCondition(string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMatchCondition (etag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMatchCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMatchCondition etag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="etag">Der ETag-Wert, auf das ETag der Ressource geprüft werden soll.</param>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur wenn der ETag-Wert der Ressource mit dem angegebenen ETag-Wert übereinstimmt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-Match-Bedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMaxSizeLessThanOrEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMaxSizeLessThanOrEqualCondition (long maxSize);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMaxSizeLessThanOrEqualCondition(int64 maxSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMaxSizeLessThanOrEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMaxSizeLessThanOrEqualCondition (maxSize As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMaxSizeLessThanOrEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMaxSizeLessThanOrEqualCondition maxSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxSize" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSize">Eine ganze Zahl, die maximale zulässige Größe des BLOBs in Bytes angeben, wenn der Commit für einen neuen Block ausgeführt.</param>
        <summary>
            Erstellt eine zugriffsbedingung, z. B., dass ein Vorgang ausgeführt wird, nur, wenn die Größe des Anhang-BLOBs nach dem Commit des Blocks kleiner als oder gleich dem angegebenen Wert ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die maximal zulässige Größe darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfModifiedSinceCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfModifiedSinceCondition (DateTimeOffset modifiedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfModifiedSinceCondition(valuetype System.DateTimeOffset modifiedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfModifiedSinceCondition(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfModifiedSinceCondition (modifiedTime As DateTimeOffset) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfModifiedSinceCondition : DateTimeOffset -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfModifiedSinceCondition modifiedTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modifiedTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="modifiedTime">Ein <see cref="T:System.DateTimeOffset" /> Wert dabei den Zeitpunkt, die seit der die Ressource geändert wurden muss.</param>
        <summary>
            Erstellt eine zugriffsbedingung, z. B., dass ein Vorgang ausgeführt wird, nur dann, wenn die Ressource seit dem angegebenen Uhrzeit geändert wurde.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-Modified-Since-Bedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNoneMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNoneMatchCondition (string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNoneMatchCondition(string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNoneMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNoneMatchCondition (etag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNoneMatchCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNoneMatchCondition etag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="etag">Der ETag-Wert, auf das ETag der Ressource, geprüft oder <c>"*"</c> anfordern, dass die Ressource nicht vorhanden ist.</param>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur wenn der ETag-Wert der Ressource nicht mit den angegebenen ETag-Wert übereinstimmt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-None-Match-Bedingung darstellt.</returns>
        <remarks>
            Wenn <c>"*"</c> wird angegeben, für die <paramref name="etag" /> Parameter, und klicken Sie dann auf diese Bedingung erfordert, dass die Ressource nicht vorhanden ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotExistsCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource nicht vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das eine Bedingung darstellt, in dem eine Ressource ist nicht vorhanden.</returns>
        <remarks>Festlegen von dieser Bedingung für den Zugriff ändert die Anforderung der HTTP einschließen <i>If-None-Match</i> bedingten Header an.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotModifiedSinceCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotModifiedSinceCondition (DateTimeOffset modifiedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotModifiedSinceCondition(valuetype System.DateTimeOffset modifiedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotModifiedSinceCondition(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotModifiedSinceCondition (modifiedTime As DateTimeOffset) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotModifiedSinceCondition : DateTimeOffset -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotModifiedSinceCondition modifiedTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modifiedTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="modifiedTime">Ein <see cref="T:System.DateTimeOffset" /> Wert, der die Zeit, die seit der die Ressource nicht Änderung angibt.</param>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die Ressource seit der angegebenen Zeit nicht geändert wurde.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-Unmodified-Since-Bedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberEqualCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberEqualCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberEqualCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberEqualCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Der Wert der aktuellen Sequenznummer verglichen werden soll.</param>
        <summary>
            Erstellt eine zugriffsbedingung, z. B., dass ein Vorgang ausgeführt wird, nur, wenn die aktuelle Sequenznummer der Ressource gleich dem angegebenen Wert ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-Sequence-Number-EQ-Bedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberLessThanCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberLessThanCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberLessThanCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Der Wert der aktuellen Sequenznummer verglichen werden soll.</param>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die aktuelle Sequenznummer der Ressource kleiner als der angegebene Wert ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-Sequence-Number-LT-Bedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberLessThanOrEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanOrEqualCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanOrEqualCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanOrEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberLessThanOrEqualCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberLessThanOrEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanOrEqualCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">Der Wert der aktuellen Sequenznummer verglichen werden soll.</param>
        <summary>
            Erstellt eine zugriffsbedingung, sodass ein Vorgang ausgeführt wird, nur, wenn die aktuelle Sequenznummer der Ressource kleiner oder gleich dem angegebenen Wert ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die If-Sequence-Number-LE-Bedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateLeaseCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateLeaseCondition (string leaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateLeaseCondition(string leaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateLeaseCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateLeaseCondition (leaseId As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateLeaseCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateLeaseCondition leaseId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leaseId">Die Lease-ID, um die Lease-ID der Ressource verglichen werden soll.</param>
        <summary>
            Erstellt eine zugriffsbedingung, dass ein Vorgang ausgeführt wird, nur, wenn die Lease-ID für die Ressource die angegebene Lease-ID übereinstimmt
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die leasebedingung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfAppendPositionEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfAppendPositionEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfAppendPositionEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfAppendPositionEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfAppendPositionEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfAppendPositionEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfAppendPositionEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert für eine Bedingung das Byte-Offset zu suchende beim Ausführen eines Commits für einen Block an ein Anhang-Blob angeben.
            Append erfolgreich nur, wenn die Endposition an diese Nummer entspricht. 
            </summary>
        <value>Eine Append-Positionsnummer oder <c>null</c> ist kein Wert festgelegt ist.</value>
        <remarks>Diese Bedingung gilt nur für Blobs Anfügen muss.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatchETag">
      <MemberSignature Language="C#" Value="public string IfMatchETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatchETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatchETag As String" />
      <MemberSignature Language="F#" Value="member this.IfMatchETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />
      <MemberType>Property</MemberType>
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
            Ruft ab oder legt einen ETag-Wert für eine Bedingung angeben, dass das ETag dem ETag der angegebenen Ressource übereinstimmen muss.
            </summary>
        <value>Eine Zeichenfolge mit einem ETag-Wert oder <c>"*"</c> für alle Etags. Wenn <c>null</c>, keine Bedingung vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMaxSizeLessThanOrEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfMaxSizeLessThanOrEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfMaxSizeLessThanOrEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMaxSizeLessThanOrEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMaxSizeLessThanOrEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfMaxSizeLessThanOrEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfMaxSizeLessThanOrEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert für eine Bedingung, die gibt die maximale Größe für ein Anhang-Blob zulässig, wenn ein neuer Block ein Commit ausgeführt wird. Append erfolgreich nur, wenn die Größe des BLOBs nach dem Anfügevorgang kleiner als oder gleich der angegebenen Größe ist.
            </summary>
        <value>Die maximale Größe in Bytes oder <c>null</c> ist kein Wert festgelegt ist.</value>
        <remarks>Diese Bedingung gilt nur für Blobs Anfügen muss.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSinceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; IfModifiedSinceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; IfModifiedSinceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSinceTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSinceTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen <see cref="T:System.DateTimeOffset" /> Wert für eine Bedingung, die Angabe einer Zeit, die seit der eine Ressource geändert wurde.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> in UTC angegebener Wert oder <c>null</c> , wenn keine Bedingung vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatchETag">
      <MemberSignature Language="C#" Value="public string IfNoneMatchETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatchETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatchETag As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatchETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />
      <MemberType>Property</MemberType>
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
            Ruft ab oder legt einen ETag-Wert für eine Bedingung angeben, dass das ETag das ETag der angegebenen Ressource nicht entsprechen muss.
            </summary>
        <value>Eine Zeichenfolge mit einem ETag-Wert oder <c>"*"</c> für alle Etags. Wenn <c>null</c>, keine Bedingung vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNotModifiedSinceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; IfNotModifiedSinceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; IfNotModifiedSinceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNotModifiedSinceTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.IfNotModifiedSinceTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen <see cref="T:System.DateTimeOffset" /> Wert für eine Bedingung, die Angabe einer Zeit, die seit der eine Ressource wurde nicht verändert.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> in UTC angegebener Wert oder <c>null</c> , wenn keine Bedingung vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert für eine Bedingung angeben, dass die aktuelle Sequenznummer gleich dem angegebenen Wert sein muss.
            </summary>
        <value>Eine Sequenznummer oder <c>null</c> , wenn keine Bedingung vorhanden ist.</value>
        <remarks>Diese Bedingung gilt nur für Seitenblobs.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberLessThan">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberLessThan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberLessThan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThan" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberLessThan As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberLessThan : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert für eine Bedingung angeben, dass die aktuelle Sequenznummer kleiner als der angegebene Wert sein muss.
            </summary>
        <value>Eine Sequenznummer oder <c>null</c> , wenn keine Bedingung vorhanden ist.</value>
        <remarks>Diese Bedingung gilt nur für Seitenblobs.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberLessThanOrEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberLessThanOrEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberLessThanOrEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThanOrEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberLessThanOrEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberLessThanOrEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThanOrEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert für eine Bedingung angeben, dem die aktuelle Sequenznummer kleiner als oder gleich dem angegebenen Wert sein muss.
            </summary>
        <value>Eine Sequenznummer oder <c>null</c> , wenn keine Bedingung vorhanden ist.</value>
        <remarks>Diese Bedingung gilt nur für Seitenblobs.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseId">
      <MemberSignature Language="C#" Value="public string LeaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LeaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.LeaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseId As String" />
      <MemberSignature Language="F#" Value="member this.LeaseId : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.LeaseId" />
      <MemberType>Property</MemberType>
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
            Ruft ab oder legt eine Lease-ID, die die Lease für eine Ressource übereinstimmen muss.
            </summary>
        <value>Eine Zeichenfolge, die eine Lease-ID enthält oder <c>null</c> , wenn keine Bedingung vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>