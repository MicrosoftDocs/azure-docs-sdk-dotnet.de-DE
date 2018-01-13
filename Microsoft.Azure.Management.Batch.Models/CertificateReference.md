<Type Name="CertificateReference" FullName="Microsoft.Azure.Management.Batch.Models.CertificateReference">
  <TypeSignature Language="C#" Value="public class CertificateReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateReference" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateReference" />
  <TypeSignature Language="F#" Value="type CertificateReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein Verweis auf ein Zertifikat auf Serverknoten in einem Pool installiert werden. Dies muss in demselben Konto als dem Pool vorhanden sein.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificateReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateReference (string id, Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; storeLocation = null, string storeName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; visibility = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; storeLocation, string storeName, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; visibility) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateReference.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.CertificateVisibility})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, Optional storeLocation As Nullable(Of CertificateStoreLocation) = null, Optional storeName As String = null, Optional visibility As IList(Of CertificateVisibility) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateReference : string * Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; -&gt; Microsoft.Azure.Management.Batch.Models.CertificateReference" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateReference (id, storeLocation, storeName, visibility)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt;" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="visibility" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Die vollqualifizierte ID des Zertifikats für den Pool zu installieren. Diese Angabe muss innerhalb der gleichen Batch-Konto mit dem Pool.</param>
        <param name="storeLocation">Der Speicherort des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</param>
        <param name="storeName">Der Name des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.</param>
        <param name="visibility">Welche Benutzerkonten auf dem Computeknoten sollte Zugriff auf die privaten Daten des Zertifikats haben.</param>
        <summary>
            Initialisiert eine neue Instanz der CertificateReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die vollständig qualifizierte ID des Zertifikats für den Pool zu installieren. Diese Angabe muss innerhalb der gleichen Batch-Konto mit dem Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; StoreLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As Nullable(Of CertificateStoreLocation)" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CertificateStoreLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicherort des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist CurrentUser. Diese Eigenschaft gilt nur für Anwendungspools, die mit Windows-Knoten (d. h. mit CloudServiceConfiguration erstellt oder mit VirtualMachineConfiguration mithilfe einer Windows-image Verweis) konfigurieren. Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird. Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden. Folgende Werte sind möglich: "CurrentUser", "LocalMachine"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Zertifikatspeichers auf den Computeknoten in die das Zertifikat zu installieren.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft gilt nur für Anwendungspools, die mit Windows-Knoten (d. h. mit CloudServiceConfiguration erstellt oder mit VirtualMachineConfiguration mithilfe einer Windows-image Verweis) konfigurieren.
            Allgemeine Namen von Läden enthalten: My, Stamm-CA, Vertrauenswürdigkeit, nicht erlaubt, TrustedPeople, TrustedPublisher, AuthRoot, AddressBook, aber ein beliebiger benutzerdefinierter Speichername kann auch verwendet werden. Der Standardwert ist My.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Visibility">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; Visibility { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; Visibility" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateReference.Visibility" />
      <MemberSignature Language="VB.NET" Value="Public Property Visibility As IList(Of CertificateVisibility)" />
      <MemberSignature Language="F#" Value="member this.Visibility : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateReference.Visibility" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="visibility")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateVisibility&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab oder legt sie fest, welche Benutzerkonten auf dem Computeknoten Zugriff auf die privaten Daten des Zertifikats erhalten soll.
             </summary>
        <value>To be added.</value>
        <remarks>
             Gültige Werte:
            
             Starttask - das Benutzerkonto, unter denen die Startaufgabe ausgeführt wird.
             Aufgabe – die Konten, unter welcher Auftrag Aufgaben ausgeführt werden.
             RemoteUser - die Konten, unter denen Benutzer den Knoten Remotezugriff auf.
             
            Sie können mehrere Sichtbarkeit in diese Sammlung angeben. Der Standardwert ist alle Konten.
             </remarks>
      </Docs>
    </Member>
  </Members>
</Type>