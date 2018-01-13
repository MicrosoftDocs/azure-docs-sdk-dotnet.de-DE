<Type Name="StoreOperationSource" FullName="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource">
  <TypeSignature Language="C#" Value="public enum StoreOperationSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StoreOperationSource extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource" />
  <TypeSignature Language="VB.NET" Value="Public Enum StoreOperationSource" />
  <TypeSignature Language="F#" Value="type StoreOperationSource = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Stellt die Quelle eines Vorgangs für den lokalen Speicher durchgeführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Local">
      <MemberSignature Language="C#" Value="Local" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource Local = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.Local" />
      <MemberSignature Language="VB.NET" Value="Local" />
      <MemberSignature Language="F#" Value="Local = 0" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.Local" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Der Vorgang wurde von einer lokalen Aktion (z. B. lokal einfügen, aktualisieren oder Löschen eines Datensatzes) ausgelöst.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LocalConflictResolution">
      <MemberSignature Language="C#" Value="LocalConflictResolution" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource LocalConflictResolution = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.LocalConflictResolution" />
      <MemberSignature Language="VB.NET" Value="LocalConflictResolution" />
      <MemberSignature Language="F#" Value="LocalConflictResolution = 1" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.LocalConflictResolution" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Vorgang wurde durch einen lokalen konfliktlösung Aktion gegen einen Vorgangsfehler ausgelöst.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LocalPurge">
      <MemberSignature Language="C#" Value="LocalPurge" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource LocalPurge = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.LocalPurge" />
      <MemberSignature Language="VB.NET" Value="LocalPurge" />
      <MemberSignature Language="F#" Value="LocalPurge = 2" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.LocalPurge" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Der Vorgang wurde durch einen lokalen Löschaktion ausgelöst.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerPull">
      <MemberSignature Language="C#" Value="ServerPull" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource ServerPull = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.ServerPull" />
      <MemberSignature Language="VB.NET" Value="ServerPull" />
      <MemberSignature Language="F#" Value="ServerPull = 3" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.ServerPull" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Der Vorgang von einem Pull-Aktion ausgelöst wurde, und gibt wieder eine neuere Version des Datensatzes vom Server.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ServerPush">
      <MemberSignature Language="C#" Value="ServerPush" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource ServerPush = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.ServerPush" />
      <MemberSignature Language="VB.NET" Value="ServerPush" />
      <MemberSignature Language="F#" Value="ServerPush = 4" Usage="Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource.ServerPush" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreOperationSource</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            Der Vorgang wurde von einer Push-Aktion ausgelöst.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>